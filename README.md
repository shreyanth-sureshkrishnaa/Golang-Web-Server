# Golang Web Server

A minimal web server written in Go using the standard `net/http` package. This project demonstrates basic routing, serving static files, and handling HTTP requests.

## Features

- Serves static files from the `./static` directory
- Handles a simple GET endpoint
- Handles a form submission using POST data
- Uses only Go’s standard library

## Running the Server

- Make sure Go is installed on your system

```bash
go build
go build main.go
```

## Features

* http://localhost:8080/ – View the static homepage

* http://localhost:8080/hello – See the hello message

* Submit the form in form.html to test the /form endpoint

