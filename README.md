= A Prometheus Workshop

This is a presentation intended to work as a workshop for
teaching Promethues, and PromQL. It contains a guided tutorial, walking
users through a simple setup of a local prometheus server, a node
exporter to explore some prometheus data, data files, and examples
of queries. The workshop was originally scheduled to run for about 2h, though
that is a little optimistic.

You can use the presentation locally using Go's present tool:

```
$ go get golang.org/x/tools/cmd/present
$ present .
```

Or use the statically comipled HTML version in the publish/ subdirectory.

The static version can be rebuilt using represent:
```
$ go get github.com/cmars/represent
$ represent -src $(pwd) -publish $(pwd)/publish       
```

