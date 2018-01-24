## 图书《Java编程的逻辑》目录

![img](./img/f640.jpg)

读者评论

前言

### 第一部分 编程基础与二进制

**第1章 编程基础**
1.1 数据类型和变量
1.2 赋值
        1.2.1 基本类型
        1.2.2 数组类型
1.3 基本运算
        1.3.1 算术运算
        1.3.2 比较运算
        1.3.3 逻辑运算
        1.3.4 小结
1.4 条件执行
        1.4.1 语法和陷阱
        1.4.2 实现原理
1.5 循环
        1.5.1 循环的4种形式
        1.5.2 循环控制
        1.5.3 实现原理
        1.5.4 小结
1.6 函数的用法
        1.6.1 基本概念
        1.6.2 进一步理解函数
        1.6.3 小结
1.7 函数调用的基本原理
        1.7.1 栈的概念
        1.7.2 函数执行的基本原理
        1.7.3 数组和对象的内存分配
        1.7.4 递归调用的原理
        1.7.5 小结

**第2章 理解数据背后的二进制**
2.1 整数的二进制表示与位运算
        2.1.1 正整数的二进制表示
        2.1.2 负整数的二进制表示
        2.1.3 十六进制
        2.1.4 位运算
2.2 小数的二进制表示
        2.2.1 小数计算为什么会出错
        2.2.2 二进制表示
2.3 字符的编码与乱码
        2.3.1 常见非Unicode编码
        2.3.2 Unicode编码
        2.3.3 编码转换
        2.3.4 乱码的原因
        2.3.5 从乱码中恢复
2.4 char的真正含义

### 第二部分 面向对象

**第3章 类的基础**
3.1 类的基本概念
        3.1.1 函数容器
        3.1.2 自定义数据类型
        3.1.3 定义第一个类
        3.1.4 使用第一个类
        3.1.5 变量默认值
        3.1.6 private变量
        3.1.7 构造方法
        3.1.8 类和对象的生命周期
        3.1.9 小结
3.2 类的组合
        3.2.1 String和Date
        3.2.2 图形类
        3.2.3 用类描述电商概念
        3.2.4 用类描述人之间的血缘关系
        3.2.5 目录和文件
        3.2.6 一些说明
        3.2.7 小结
3.3 代码的组织机制
        3.3.1 包的概念
        3.3.2 jar包
        3.3.3 程序的编译与链接
        3.3.4 小结

**第4章 类的继承**
4.1 基本概念
        4.1.1 根父类Object
        4.1.2 方法重写
        4.1.3 图形类继承体系
        4.1.4 小结
4.2 继承的细节
        4.2.1 构造方法
        4.2.2 重名与静态绑定
        4.2.3 重载和重写
        4.2.4 父子类型转换
        4.2.5 继承访问权限protected
        4.2.6 可见性重写
        4.2.7 防止继承final
4.3 继承实现的基本原理
        4.3.1 示例
        4.3.2 类加载过程
        4.3.3 对象创建的过程
        4.3.4 方法调用的过程
        4.3.5 变量访问的过程
4.4 为什么说继承是把双刃剑
        4.4.1 继承破坏封装
        4.4.2 封装是如何被破坏的
        4.4.3 继承没有反映is-a关系
        4.4.4 如何应对继承的双面性

**第5章 类的扩展**
5.1 接口的本质
        5.1.1 接口的概念
        5.1.2 定义接口
        5.1.3 实现接口
        5.1.4 使用接口
        5.1.5 接口的细节
        5.1.6 使用接口替代继承
        5.1.7 Java 8和Java 9对接口的增强
        5.1.8 小结
5.2 抽象类
        5.2.1 抽象方法和抽象类
        5.2.2 为什么需要抽象类
        5.2.3 抽象类和接口
        5.2.4 小结
5.3 内部类的本质
        5.3.1 静态内部类
        5.3.2 成员内部类
        5.3.3 方法内部类
        5.3.4 匿名内部类
5.4 枚举的本质
        5.4.1 基础
        5.4.2 典型场景

**第6章 异常**
6.1 初识异常
        6.1.1 NullPointerException（空指针异常）
        6.1.2 NumberFormatException（数字格式异常）
6.2 异常类
        6.2.1 Throwable
        6.2.2 异常类体系
        6.2.3 自定义异常
6.3 异常处理
        6.3.1 catch匹配
        6.3.2 重新抛出异常
        6.3.3 finally
        6.3.4 try-with-resources
        6.3.5 throws
        6.3.6 对比受检和未受检异常
6.4 如何使用异常
        6.4.1 异常应该且仅用于异常情况
        6.4.2 异常处理的目标
        6.4.3 异常处理的一般逻辑

**第7章 常用基础类**
7.1 包装类
        7.1.1 基本用法
        7.1.2 共同点
        7.1.3 剖析Integer与二进制算法
        7.1.4 剖析Character
7.2 剖析String
        7.2.1 基本用法
        7.2.2 走进String内部
        7.2.3 编码转换
        7.2.4 不可变性
        7.2.5 常量字符串
        7.2.6 hashCode
        7.2.7 正则表达式
7.3 剖析StringBuilder
        7.3.1 基本用法
        7.3.2 基本实现原理
        7.3.3 String的+和+ =运算符
7.4 剖析Arrays
        7.4.1 用法
        7.4.2 多维数组
        7.4.3 实现原理
        7.4.4 小结
7.5 剖析日期和时间
        7.5.1 基本概念
        7.5.2 日期和时间API
        7.5.3 局限性
7.6 随机
        7.6.1 Math.random
        7.6.2 Random
        7.6.3 随机的基本原理
        7.6.4 随机密码
        7.6.5 洗牌
        7.6.6 带权重的随机选择
        7.6.7 抢红包算法
        7.6.8 北京购车摇号算法
        7.6.9 小结

### 第三部分 泛型与容器

**第8章 泛型**
8.1 基本概念和原理
        8.1.1 一个简单泛型类
        8.1.2 容器类
        8.1.3 泛型方法
        8.1.4 泛型接口
        8.1.5 类型参数的限定
        8.1.6 小结
8.2 解析通配符
        8.2.1 更简洁的参数类型限定
        8.2.2 理解通配符
        8.2.3 超类型通配符
        8.2.4 通配符比较
8.3 细节和局限性
        8.3.1 使用泛型类、方法和接口
        8.3.2 定义泛型类、方法和接口
        8.3.3 泛型与数组
        8.3.4 小结

**第9章 列表和队列**
9.1 剖析ArrayList
        9.1.1 基本用法
        9.1.2 基本原理
        9.1.3 迭代
        9.1.4 ArrayList实现的接口
        9.1.5 ArrayList的其他方法
        9.1.6 ArrayList特点分析
        9.1.7 小结
9.2 剖析LinkedList
        9.2.1 用法
        9.2.2 实现原理
        9.2.3 LinkedList特点分析
9.3 剖析ArrayDeque
        9.3.1 实现原理
        9.3.2 ArrayDeque特点分析

**第10章 Map和Set**
10.1 剖析HashMap
        10.1.1 Map接口
        10.1.2 HashMap
        10.1.3 实现原理
        10.1.4 小结
10.2 剖析HashSet
        10.2.1 用法
        10.2.2 实现原理
        10.2.3 小结
10.3 排序二叉树
        10.3.1 基本概念
        10.3.2 基本算法
        10.3.3 平衡的排序二叉树
        10.3.4 小结
10.4 剖析TreeMap
        10.4.1 基本用法
        10.4.2 实现原理
        10.4.3 小结
10.5 剖析TreeSet
        10.5.1 基本用法
        10.5.2 实现原理
        10.5.3 小结
10.6 剖析LinkedHashMap
        10.6.1 基本用法
        10.6.2 实现原理
        10.6.3 LinkedHashSet
        10.6.4 小结
10.7 剖析EnumMap
        10.7.1 基本用法
        10.7.2 实现原理
        10.7.3 小结
10.8 剖析EnumSet
        10.8.1 基本用法
        10.8.2 应用场景
        10.8.3 实现原理
        10.8.4 小结

**第11章 堆与优先级队列**
11.1 堆的概念与算法
        11.1.1 基本概念
        11.1.2 堆的算法
        11.1.3 小结
11.2 剖析PriorityQueue
        11.2.1 基本用法
        11.2.2 实现原理
        11.2.3 小结
11.3 堆和PriorityQueue的应用
        11.3.1 求前K个最大的元素
        11.3.2 求中值
        11.3.3 小结

**第12章 通用容器类和总结**
12.1 抽象容器类
        12.1.1 AbstractCollection
        12.1.2 AbstractList
        12.1.3 AbstractSequentialList
        12.1.4 AbstractMap
        12.1.5 AbstractSet
        12.1.6 AbstractQueue
        12.1.7 小结
12.2 Collections
        12.2.1 查找和替换
        12.2.2 排序和调整顺序
        12.2.3 添加和修改
        12.2.4 适配器
        12.2.5 装饰器
        12.2.6 小结
12.3 容器类总结
        12.3.1 用法和特点
        12.3.2 数据结构和算法
        12.3.3 设计思维和模式

### 第四部分 文件

**第13章 文件基本技术**
13.1 文件概述
        13.1.1 基本概念和常识
        13.1.2 Java文件概述
13.2 二进制文件和字节流
        13.2.1 InputStream/OutputStream
        13.2.2 FileInputStream/File-OutputStream
        13.2.3 ByteArrayInputStream/ByteArrayOutputStream
        13.2.4 DataInputStream/Data-OutputStream
        13.2.5 BufferedInputStream/BufferedOutputStream
        13.2.6 实用方法
        13.2.7 小结
13.3 文本文件和字符流
        13.3.1 基本概念
        13.3.2 Reader/Writer
        13.3.3 InputStreamReader/Output-StreamWriter
        13.3.4 FileReader/FileWriter
        13.3.5 CharArrayReader/Char-ArrayWriter
        13.3.6 StringReader/StringWriter
        13.3.7 BufferedReader/Buffered-Writer
        13.3.8 PrintWriter
        13.3.9 Scanner
        13.3.10 标准流
        13.3.11 实用方法
        13.3.12 小结
13.4 文件和目录操作
        13.4.1 构造方法
        13.4.2 文件元数据
        13.4.3 文件操作
        13.4.4 目录操作

**第14章 文件高级技术**
14.1 常见文件类型处理
        14.1.1 属性文件
        14.1.2 CSV文件
        14.1.3 Excel
        14.1.4 HTML
        14.1.5 压缩文件
14.2 随机读写文件
        14.2.1 用法
        14.2.2 设计一个键值数据库BasicDB
        14.2.3 BasicDB的实现
        14.2.4 小结
14.3 内存映射文件
        14.3.1 基本概念
        14.3.2 用法
        14.3.3 设计一个消息队列BasicQueue
        14.3.4 实现消息队列
        14.3.5 小结
14.4 标准序列化机制
        14.4.1 基本用法
        14.4.2 复杂对象
        14.4.3 定制序列化
        14.4.4 序列化的基本原理
        14.4.5 版本问题
        14.4.6 序列化特点分析
14.5 使用Jackson序列化为JSON/XML/MessagePack
        14.5.1 基本概念
        14.5.2 基本用法
        14.5.3 容器对象
        14.5.4 复杂对象
        14.5.5 定制序列化
        14.5.6 Jackson对XML支持的局限性
        14.5.7 小结

### 第五部分 并发

**第15章 并发基础知识**
15.1 线程的基本概念
        15.1.1 创建线程
        15.1.2 线程的基本属性和方法
        15.1.3 共享内存及可能存在的问题
        15.1.4 线程的优点及成本
15.2 理解synchronized
        15.2.1 用法和基本原理
        15.2.2 进一步理解synchronized
        15.2.3 同步容器及其注意事项
15.3 线程的基本协作机制
        15.3.1 协作的场景
        15.3.2 wait/notify
        15.3.3 生产者/消费者模式
        15.3.4 同时开始
        15.3.5 等待结束
        15.3.6 异步结果
        15.3.7 集合点
        15.3.8 小结
15.4 线程的中断
        15.4.1 取消/关闭的场景
        15.4.2 取消/关闭的机制
        15.4.3 线程对中断的反应
        15.4.4 如何正确地取消/关闭线程
        15.4.5 小结

**第16章 并发包的基石**
16.1 原子变量和CAS
        16.1.1 AtomicInteger
        16.1.2 ABA问题
        16.1.3 小结
16.2 显式锁
        16.2.1 接口Lock
        16.2.2 可重入锁ReentrantLock
        16.2.3 ReentrantLock的实现原理
        16.2.4 对比ReentrantLock和synchronized
16.3 显式条件
        16.3.1 用法
        16.3.2 生产者/消费者模式
        16.3.3 实现原理
        16.3.4 小结

**第17章 并发容器**
17.1 写时复制的List和Set
        17.1.1 CopyOnWriteArrayList
        17.1.2 CopyOnWriteArraySet
17.2 ConcurrentHashMap
        17.2.1 并发安全
        17.2.2 原子复合操作
        17.2.3 高并发的基本机制
        17.2.4 迭代安全
        17.2.5 弱一致性
        17.2.6 小结
17.3 基于跳表的Map和Set
        17.3.1 基本概念
        17.3.2 基本实现原理
17.4 并发队列
        17.4.1 无锁非阻塞并发队列
        17.4.2 普通阻塞队列
        17.4.3 优先级阻塞队列
        17.4.4 延时阻塞队列
        17.4.5 其他阻塞队列

**第18章 异步任务执行服务**
18.1 基本概念和原理
        18.1.1 基本接口
        18.1.2 基本用法
        18.1.3 基本实现原理
        18.1.4 小结
18.2 线程池
        18.2.1 理解线程池
        18.2.2 工厂类Executors
        18.2.3 线程池的死锁
        18.2.4 小结
18.3 定时任务的那些陷阱
        18.3.1 Timer和TimerTask
        18.3.2 ScheduledExecutorService
        18.3.3 小结

**第19章 同步和协作工具类**
19.1 读写锁ReentrantReadWrite-Lock
19.2 信号量Semaphore
19.3 倒计时门栓CountDownLatch
19.4 循环栅栏CyclicBarrier
19.5 理解ThreadLocal
        19.5.1 基本概念和用法
        19.5.2 使用场景
        19.5.3 基本实现原理

**第20章 并发总结**
20.1 线程安全的机制
20.2 线程的协作机制
20.3 容器类
20.4 任务执行服务

### 第六部分 动态与函数式编程

**第21章 反射**
21.1 Class类
21.2 应用示例
21.3 反射与泛型

**第22章 注解**
22.1 内置注解
22.2 框架和库的注解
22.3 创建注解
22.4 查看注解信息
22.5 注解的应用：定制序列化
22.6 注解的应用：DI容器

**第23章 动态代理**
23.1 静态代理
23.2 Java SDK动态代理
        23.2.1 用法
        23.2.2 基本原理
        23.2.3 动态代理的优点
23.3 cglib动态代理
23.4 Java SDK代理与cglib代理比较
23.5 动态代理的应用：AOP
        23.5.1 用法
        23.5.2 实现原理

**第24章 类加载机制**
24.1 类加载的基本机制和过程
24.2 理解ClassLoader
24.3 类加载的应用：可配置的策略
24.4 自定义ClassLoader
24.5 自定义ClassLoader的应用：热部署

**第25章 正则表达式**
25.1 语法
25.2 Java API
25.3 模板引擎
25.4 剖析常见表达式

**第26章 函数式编程**
26.1 Lambda表达式
        26.1.1 通过接口传递代码
        26.1.2 Lambda语法
        26.1.3 函数式接口
        26.1.4 预定义的函数式接口
        26.1.5 方法引用
        26.1.6 函数的复合
        26.1.7 小结
26.2 函数式数据处理：基本用法
        26.2.1 基本示例
        26.2.2 中间操作
        26.2.3 终端操作
        26.2.4 构建流
        26.2.5 函数式数据处理思维
26.3 函数式数据处理：强大方便的收集器
        26.3.1 理解collect
        26.3.2 容器收集器
        26.3.3 字符串收集器
        26.3.4 分组
26.4 组合式异步编程
        26.4.1 异步任务管理
        26.4.2 与Future/FutureTask对比
        26.4.3 响应结果或异常
        26.4.4 构建依赖单一阶段的任务流
        26.4.5 构建依赖两个阶段的任务流
        26.4.6 构建依赖多个阶段的任务流
        26.4.7 小结
26.5 Java 8的日期和时间API
        26.5.1 表示日期和时间
        26.5.2 格式化
        26.5.3 设置和修改时间
        26.5.4 时间段的计算

        26.5.5 与Date/Calendar对象的转换

------

京东购买链接：

http://item.jd.com/12299018.html