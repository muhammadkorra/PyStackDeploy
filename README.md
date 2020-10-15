# PyStackDeploy
Simple library providing `docker stack deploy` functionality in Python through `docker.DockerClient` in Docker's official Python SDK.

## Usage
> Still under development but usage should look like this
```python
import PyCompose from pystackdeploy
import docker

client = docker.DockerClient(base_url='unix://var/run/docker.sock')
pycomp = PyCompose(client, 'docker-compose.yml')
pycomp.deploy()
```
