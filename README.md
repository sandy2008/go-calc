# go-calc
goyacc calculator example in Go

# How to run
```
go get golang.org/x/tools/cmd/goyacc
go install golang.org/x/tools/cmd/goyacc
goyacc -o parser.go parser.go.y
go run parser.go "1+2*4-6/3"
```
