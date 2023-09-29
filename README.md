# Go Rate Limit Methods

- Token Bucket Algorithm
- Per-client rate limiting
- Using tollbooth as middleware

## Useful Links

- [Tollbooth](github.com/didip/tollbooth/v7)
- [How to Rate Limit HTTP Requests](https://www.alexedwards.net/blog/how-to-rate-limit-http-requests)
- [Rate Limiting in Go Application](https://blog.logrocket.com/rate-limiting-go-application/)

## To Run

- cd into the project directory
- run `go run main.go`
- in another terminal, run

```bash
curl -i http://localhost:8080/ping;
curl -i http://localhost:8080/ping;
curl -i http://localhost:8080/ping;
curl -i http://localhost:8080/ping;
curl -i http://localhost:8080/ping;
curl -i http://localhost:8080/ping;
```
