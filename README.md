This small example will load the bbc homepage and print it to the stdout.
The http request experiences a time out with MacOS Monterey 12.6.1, (chip M1 Pro).  
The code works with MacOS Ventura 13.0, (2.3 GHz 8-Core Intel Core i9)

The aim is to force Go to use the netgo implementation instead of the cgo implement of the net package.

```sh
export CGO_ENABLED=0 go run main.go
```

