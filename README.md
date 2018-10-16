# knows
一些知识库

参考网址：https://www.jianshu.com/p/9417650cad5f


### Code block
```
slaveof <masterip> <masterport>
# masterip为主节点IP地址，masterport为主节点端口
slave-read-only yes                     
# 从节点只做读操作，不做写操作，保证主从设备数据相同
```
