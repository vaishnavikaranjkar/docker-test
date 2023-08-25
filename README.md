##### Running flask app from Docker CLI in Windows 11

- Ensure Docker Desktop is running 
- Check running container, images and processes:
    docker container ls
    docker images
    docker ps

- Docker CLI
1. Building docker image from python file:
    $ docker image build -t python-hello-world .
2. Run container
    $ docker run -p 5001:5000 -d python-hello-world

-App is running on - http://localhost:5001
