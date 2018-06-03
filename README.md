Getting Started

  Running docker-compose up is all you need. It will:
  Build custom local image enabled for development (nodemon, NODE_ENV=development).
  Start container from that image with ports 80, 5858, and 9229 open (on localhost).
  Starts with nodemon to restart node on file change in host pwd.
  Mounts the pwd to the app dir in container.
  Be sure to use docker-compose down to cleanup after your done dev'ing.
