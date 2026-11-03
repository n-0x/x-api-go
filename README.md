# x-api-go

Generated from [n-0x/x-api](https://github.com/n-0x/x-api); do not edit generated code.
The Go module is `github.com/n-0x/x-api-go` (Go 1.26 or later).

`sync.yml` polls every 15 minutes. To regenerate a specific source tag, run:

```sh
gh workflow run sync.yml -R n-0x/x-api-go -f tag=vX.Y.Z
```

The workflow builds and commits the generated client on `main`, then publishes the
same tag. Existing tags are left unchanged. Consumers select a released tag with
`go get github.com/n-0x/x-api-go@vX.Y.Z` and never generate code themselves.
