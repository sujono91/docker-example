## Docker for React in Production

How to run the dev server and unit test with hot-reload:
```
1. docker-compose up
2. Open http://localhost:3000
```

How to run the build result:
```
1. docker build . -t [Docker Username]/[Image Name]
2. docker run -p [Desired Port]:80 [Docker Username]/[Image Name]
```

Example:
```
1. docker build . -t sujono91/frontend:latest
2. docker run -p 8080:80 sujono91/frontend
```