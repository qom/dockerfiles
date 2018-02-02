FROM foundation

# Create user to run cassandra as
RUN useradd -ms /bin/bash cassandra
USER cassandra
WORKDIR /home/cassandra

COPY apache-cassandra-2.1.17-bin.tar.gz .
RUN tar -xzf apache-cassandra-2.1.17-bin.tar.gz



