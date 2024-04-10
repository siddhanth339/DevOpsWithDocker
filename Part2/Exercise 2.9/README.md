Added build commands to the docker-compose.yml files to create new images for frontend and backend as their dockerfiles were updated.

Specifically, the ENV REACT_APP_BACKEND_URL variable in frontend Dockerfile was updated to http://localhost/api based on the nginx configuration.
