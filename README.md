## What To Learn？

看了一位starrocks的数据库研发工程师的[blog](https://blog.bcmeng.com/)之后，才知道数据库也牵涉到如此多底层设计与实现的性能优化。

如下图所示，从内存管理优化、CPU 性能利用（如CPU cache和SIMD优化）到上层的 C++ Low Level 优化、数据结构和算法、高性能第三方库，每部分都有极大的性能榨取空间

![数据库优化架构](pics/数据库优化架构.jpg)



#### wonderful resources

[starrocks康](https://blog.bcmeng.com/post/database-learning.html)

[pingcap](https://github.com/pingcap/awesome-database-learning)

#### long-term plans

- [ ] 高性能计算
- [ ] 列存及伴随的优化
- [ ] 数据库的编译执行
- [ ] 数据库的查询优化

#### Short-term plans

- [ ] 查询层

  - [ ] 执行

  - [ ] 优化
    - [ ] [Efficiency in the Columbia Database Query Optimizer](https://15721.courses.cs.cmu.edu/spring2018/papers/15-optimizer1/xu-columbia-thesis1998.pdf)
    - [ ] [The Cascades Framework for Query Optimization](https://15721.courses.cs.cmu.edu/spring2018/papers/15-optimizer1/graefe-ieee1995.pdf)
    - [ ] [The Volcano Optimizer Generator: Extensibility and Efficient Search](https://cs.uwaterloo.ca/~david/cs848/volcano.pdf)
    - [ ] [Noisepage Optimizer](https://github.com/cmu-db/terrier/tree/master/src/optimizer)

