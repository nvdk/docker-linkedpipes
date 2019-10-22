FROM maven:3
ADD https://codeload.github.com/linkedpipes/etl/tar.gz/master /linkedpipes.tar.gz
RUN mkdir /build && cd /build && tar xvzf /linkedpipes.tar.gz && cd etl-master && mvn install