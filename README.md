# docker-fastapi-test

maps port 8000 of the container to port 8000 on the host machine.

Open your browser and go to http://127.0.0.1:8000. You should see:
{"message": "Hello World"}

Open http://127.0.0.1:8000 to check the running app.
# Dockerfile:
Specifies how to build the Docker image, installing dependencies, copying files, and setting the command to run the server.
# docker-compose.yml:
Helps manage multiple containers and simplify the deployment process by using a single command.
