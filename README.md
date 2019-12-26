

# llrp
Official golang implement Low Level Reader Protocol(LLRP)
## Document and reference
You can get there in this repo.
## How to run test
```   go run main.go ```
By default it will connect to physical reader (speed way) IP `192.168.33.16` and port `5084`

## Add more functionality
List of function I implement base on we used. So if you want to add more function of this package go to `request.go` ,`respone.go` and `param_parse.go` files.These files are core of this package.
### 
 
## main developer
Pichit Rintara (Thailand) - pictca@gmail.com

## Issue & bug report
Currently, I don't have physical reader. If you found some bug relate on function in this project.
please attach snap tcp package file (use tool like [wireshark](https://www.wireshark.org/download.html))
while running main demo.
