# Go Release Actions

Combine several action to do auto-release

```yml
- uses: t-actions/go-release@master
  with:
    # Tag for release
    tag:

    # Token for call API, default ${{ github.token }}
    token:

    # Input parameters for build, default is root folder
    input:

    # Output folder for build result
    # Default: 'build'
    output:

    # Platforms for go build, default is result of `go tool dist list`
    platforms:

    # Prebuild script
    prebuild:
```
