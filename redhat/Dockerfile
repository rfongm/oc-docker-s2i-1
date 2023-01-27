# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# Cambiar los parametros para generar una nueva salida el OCP del POD
# CMD ["/bin/bash", "-c", "sleep infinity"]
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
