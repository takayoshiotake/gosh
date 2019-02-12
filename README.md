# gosh

Run $GOBIN/* easily even without $GOBIN and $GOPATH.

## Installation

```
$ brew tap takayoshiotake/tap
$ brew install gosh
```

## Usage

```
$ gosh [Go package]
```

e.g.

```
$ go get -u github.com/golang/dep/cmd/dep
$ echo $GOBIN, $GOPATH
,
$ gosh dep version
dep:
 version     : devel
 build date  : 
 git hash    : 
 go version  : go1.11.2
 go compiler : gc
 platform    : darwin/amd64
 features    : ImportDuringSolve=false
```
