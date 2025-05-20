FROM pytorch/pytorch:2.6.0-cuda12.6-cudnn9-devel

RUN apt-get update && \
    apt-get -y upgrade && \
    apt-get install ffmpeg libsm6 libxext6 -y

RUN pip install --upgrade pip