# gin-gonic.com-docs-examples-binding-and-validation

- Model binding and validation

- Reference: https://gin-gonic.com/docs/examples/binding-and-validation/

## gvm

```sh
gvm install go1.23.5
gvm use go1.23.5
```

## go get

```sh
go get .
```

## go run

```sh
go run .
```

## cURL

- login

```sh
curl --location 'localhost:8080/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "user": "admin",
    "password": "Aa@123456"
}'
```
