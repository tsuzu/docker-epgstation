FROM chinachu/mirakurun

RUN apt-get update && apt-get install -y git automake autoconf && \
    git clone https://github.com/stz2012/recpt1 /tmp/recpt1 && \
    cd /tmp/recpt1/recpt1 && \
    ./autogen.sh && \
    ./configure && \
    make && \
    make install
