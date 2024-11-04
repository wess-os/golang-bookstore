# golang-bookstore

## Routes

```bash
http://localhost:9010/
```

| Method | Endpoint | Description |
| ------ | -------- | ----------- |
| POST   | /book    | Create a new book |
| GET    | /book    | Get all books |
| GET    | /book/{bookId} | Get a book by id |
| PUT    | /book/{bookId} | Update a book by id |
| DELETE | /book/{bookId} | Delete a book by id |

## Configuration
1.
    - Change the database configuration in the file `pkg/config/app.go`

## Run
1.
```bash
go build cmd/main
```

2.
```bash
go run cmd/main/main.go
```
