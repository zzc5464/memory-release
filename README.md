# memory-release（内存回收机制）
> 每个函数都有自己的生命周期
## 内存分配
- 当我们声明变量、函数、对象的时候，系统会自动给他们分配内存空间
- 使用完毕，会被js的内存回收机制自动回收。
## 栈和堆内存
- 存放在栈内存的数据，就像数组一样，每调用一次相当于数组+1;
- 当数组长度为0的时候就释放内存
## 堆内存
- 引用计数
> 创建一个构造函数，当每实例化一次引用计数+1.
> 同样的当没有人再调用他的时候，内存自动释放
###
> 至于怎么回收，那就是更底层的内容了。。。有关于c++什么的，暂时还不懂











