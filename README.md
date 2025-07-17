# Abhishek-project-steps


1.run the application locally----------------
step-1---------clone repo----ls---

go build -o main .--repo main
run it---./main
____________________
write docker file now---
multi-stage-docker-file
stage1---build docker image---download dep---once application built
stage2---use distroless image-----copy build in stage1----expose the port and run application

