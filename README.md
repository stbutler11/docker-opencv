OpenCV Docker
========

This creates an image of [OpenCV | http://opencv.org/] on Ubuntu 14.04.

I used the steps outlined in this [blog post](http://www.samontab.com/web/2014/06/installing-opencv-2-4-9-in-ubuntu-14-04-lts/) to create the image.

This image has been push up to the [docker registry](https://registry.hub.docker.com/u/stbutler11/opencv2.4.9/).

## Running

You can play around with this image by running:

```docker run -ti stbutler11/opencv2.4.9 /bin/bash```

## Building

Standard docker

```docker build . ```