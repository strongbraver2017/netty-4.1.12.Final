# netty-4.1.12.Final
netty-4.1.12.Final source code, can compile in Win10 with Maven 3.3.9

Of course source code come from [netty-4.1.12.Final](https://github.com/netty/netty/releases/tag/netty-4.1.12.Final), and **The missing netty collection** source code come from [io/netty/util/collection/](https://github.com/txazo/netty/tree/master/src/main/java/io/netty/util/collection)

## 说明
为了方便直接把netty-4.1.12 Final的源码整合成一个Maven项目，且在Win10下的Maven 3.3.9下编译通过，目前里面没有包括test测试目录（因为测试还依赖其他一些jar包），仅仅只有源码，目的是为了便于学习（例如修改源码或者给源码加注释什么的）

上面也提到官方netty github上的源码**缺少io/netty/util/collection**包的源码，很是奇怪（或许是我没找到？），后来在[这里找到了]([io/netty/util/collection/](https://github.com/txazo/netty/tree/master/src/main/java/io/netty/util/collection))，该项目作者提到是netty-4.1.1.Final的源码，那为什么现在netty-4.1.12.Final就没有了呢？