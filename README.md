# Setup ZooKeeper

- Download ZooKeeper: https://zookeeper.apache.org/releases.html
- Download Java runtime: https://formulae.brew.sh/formula/openjdk@17
- Run ZooKeeper: `bin/zkServer.sh start`
- Connect to ZooKeeper: `bin/zkCli.sh -server 127.0.0.1:2181`

# Reference

- [MIT 6.824: Distributed Systems - Lecture 8: Zookeeper](https://www.youtube.com/watch?v=pbmyrNjzdDk)
- [MIT 6.824: Distributed Systems - Lecture 9: More Replication, CRAQ](https://www.youtube.com/watch?v=IXHzbCuADt0)
- [Building an asynchronous ZooKeeper client in Rust](https://www.youtube.com/watch?v=mMuk8Rn9HBg)
- [Building an asynchronous ZooKeeper client in Rust (part 2)](https://www.youtube.com/watch?v=0-Fsu-aM0_A)
- [Building an asynchronous ZooKeeper client in Rust (part 3)](https://www.youtube.com/watch?v=1ADDeB9rqAI)
- https://github.com/stackabletech/tokio-zookeeper
