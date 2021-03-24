# Run
     cmd:   cd .\src\
     cmd:   go run .\main.go
    
---
# Build
     cmd: docker build \
         --build-arg USER_ID=$(id -u) \
         --build-arg GROUP_ID=$(id -g) \
         -t mathapp-development .

----
# Source
## How To Deploy a Go Web Application with Docker [semaphoreci.com](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker).