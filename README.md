# Golang GRPC

Project showcasing using grpc instead of the usual suspect which is http requests with json data.


### Generate proto files
To generate golang proto files run this command:
```
protoc -I proto proto/contracts/*.proto --go_out=./proto/gen/go/ --go_opt=paths=source_relative --go-grpc_out=./proto/gen/go/ --go-grpc_opt=paths=source_relative

```