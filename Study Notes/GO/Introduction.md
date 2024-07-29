```go
package main

import "fmt"

func main() {
    fmt.Print("Hello World")
}
```

- `fmt` is a in-built package that has a function `Print`
- Go file starts with `package`
- Go Application can consist of one or more package, but at least one package and a package can have more than one file
- We can use parts of package A in package B by exporting and importing the package 
- `main` package is a special package as it is the entry point of the program
- `go build` creates a executable file that can run on any system even on ones that don't have go installed.
- A module is a collection of related packages
- To initialize a module `go mod init path_to_module` like `go mod init example.com/first-app`
- Inside `main` package should contain a function `main` which serves as a entry point of module
- So in simpler terms a project is a module that contains one or more than one packages, with at least one named main which has one main function which serves as the entry point of complete project/module  