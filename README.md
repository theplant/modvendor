modvendor
=========

Simple tool to copy additional module files into a local ./vendor folder. This
tool should be run after `go mod vendor`.

`go get -u github.com/theplant/modvendor`

## Usage

```
$ modvendor -copy="**/*.c **/*.h **/*.proto" -v
```

## LICENSE

MIT
