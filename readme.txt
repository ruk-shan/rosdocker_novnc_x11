Run ros-melodic docker image with X11 and NoVNC

#Build
$ docker build -t doctest3:v3 .

#Run
$ docker run --rm -it -p 8087:8080 doctest3:v3
