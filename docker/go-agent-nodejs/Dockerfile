FROM gocd/gocd-agent-debian-8:v17.12.0
ARG NODE_VERSION=9.4.0
WORKDIR /opt/
ADD https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz node-v$NODE_VERSION-linux-x64.tar.xz
RUN apt install xz-utils bzip2 && \
    tar -xf node-v$NODE_VERSION-linux-x64.tar.xz && \
    ln -nfs /opt/node-v9.4.0-linux-x64/bin/* /usr/bin/.
