# github
git clone git@github.com:onemkim/goProject.git
git status
git add --all
git commit -a -m "Comment"
git push


# goProject
This is the first change after creation.

module
go mod init github.com/onemkim/goProject
go test
go list -m all

go get rsc.io/sampler
go mod tidy


rm -rf filterName


Comment - https://blog.golang.org/using-go-modules
go mod init creates a new module, initializing the go.mod file that describes it.
go build, go test, and other package-building commands add new dependencies to go.mod as needed.
go list -m all prints the current module’s dependencies.
go get changes the required version of a dependency (or adds a new dependency).
go mod tidy removes unused dependencies.


Playground
https://play.golang.org

go fmt
go run main.go
