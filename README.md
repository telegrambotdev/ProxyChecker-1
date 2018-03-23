# ProxyChecker
http proxy checker

# Getting Started

Checker accept txt file with proxies which look like this

```
80.211.231.6:3128
80.211.4.187:8080
80.246.74.206:8080
80.59.199.213:8080
80.72.66.212:8081
80.73.9.75:3128
```

For start checker type
```
go run checker.go
```
Or compile it into executable file

Set the path to txt file with proxies
```
Enter path to file: C:\Documents\proxy.txt
```
And push Enter

After checker complete, he create file `live-proxies.txt` and put valid proxies to it.

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details