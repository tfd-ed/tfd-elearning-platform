<h1>TFD E-Learning Platform </h1>  
<p align="center">  
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" width="75">  
<img src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white" width="80">  
<img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" width="100">  
<img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" width="70">  
<img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" width="73">  
<img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" width="90">  
<img src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white" width="70">  
<img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white" width="60">  
<br/>  
<a href="https://www.mit.edu/~amini/LICENSE.md" target="_blank"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="Package License" /></a>  
<img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/UCJHZ__wUxS9lgTZHMxpMJcQ?style=social">  
</p>  

## TFD E-Learning's Components
- TFD Blog (Now TFD E-Learning) : https://github.com/tfd-ed/tfd-blog
- TFD E-Learning Admin: https://github.com/tfd-ed/tfd-elearning-admin
- TFD E-Learning API: https://github.com/tfd-ed/tfd-nest-blog-api

## Setup Guide
### Initialize Environment Variable
- There are 4 environment templates `.env.template`, `.env.server.template`, `.env.client.template`, `.env.admin.template`.
- Make your own env file by copy all the content and replace them with your own into new env files. `.env`, `.env.server`, etc 
### With Docker
Make sure you have your [docker](https://docs.docker.com/engine/install/) setup and running.
Run the following scripts for UNIX (Mac,Linux)
```bash  
$ docker compose up -d
```  

## Available Services with Docker Container
Once you managed to run the docker container, the following service will be available:
- Swagger API Docs (http://localhost:3525/docs/)
- Database (Postgres 12) (http://localhost:5432)
- Frontend (User) (http://localhost:6662)
- Frontend (Admin) (http://localhost:4633)
