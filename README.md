[![HitCount](http://hits.dwyl.io/yuhaiqiang/https://githubcom/yuhaqiang123/my-love.svg)](http://hits.dwyl.io/yuhaiqiang/https://githubcom/yuhaqiang123/my-love)
<details><summary>并发编程总结.pic_hd</summary><img src="并发编程总结.pic_hd.jpg"  alt="并发编程总结.pic_hd" /></details>
<details><summary>AQS</summary><img src="img/AQS.png"  alt="AQS" /></details>
<details><summary>如何快速融入团队</summary><img src="img/如何快速融入团队.png"  alt="如何快速融入团队" /></details>
<details><summary>架构-微服务</summary><img src="img/架构-微服务.png"  alt="架构-微服务" /></details>
<details><summary>Dubbo</summary><img src="img/Dubbo.png"  alt="Dubbo" /></details>
<details><summary>IO 多路复用</summary><img src="img/IO 多路复用.png"  alt="IO 多路复用" /></details>
<details><summary>系统编程& 进程线程管理</summary><img src="img/系统编程& 进程线程管理.png"  alt="系统编程& 进程线程管理" /></details>
<details><summary>CompletableFuture</summary><img src="img/CompletableFuture.png"  alt="CompletableFuture" /></details>
<details><summary>信号& 中断</summary><img src="img/信号& 中断.png"  alt="信号& 中断" /></details>
<details><summary>线程池 的其他使用</summary><img src="img/线程池 的其他使用.png"  alt="线程池 的其他使用" /></details>
<details><summary>进程管理与调度算法</summary><img src="img/进程管理与调度算法.png"  alt="进程管理与调度算法" /></details>
<details><summary>gc</summary><img src="img/gc.png"  alt="gc" /></details>
<details><summary>管道&FIFO</summary><img src="img/管道&FIFO.png"  alt="管道&FIFO" /></details>
<details><summary>文件IO   内存管理</summary><img src="img/文件IO   内存管理.png"  alt="文件IO   内存管理" /></details>
<details><summary>分布式&&zookeeper</summary><img src="img/分布式&&zookeeper.png"  alt="分布式&&zookeeper" /></details>
<details><summary>Spring</summary><img src="img/Spring.png"  alt="Spring" /></details>
<details><summary>web socket</summary><img src="img/web socket.png"  alt="web socket" /></details>
<details><summary>如何设计一个服务框架</summary><img src="img/如何设计一个服务框架.png"  alt="如何设计一个服务框架" /></details>
<details><summary>Java 锁和线程</summary><img src="img/Java 锁和线程.png"  alt="Java 锁和线程" /></details>
<details><summary>通用</summary><img src="img/通用.png"  alt="通用" /></details>
<details><summary>nginx</summary><img src="img/nginx.png"  alt="nginx" /></details>
<details><summary>零拷贝& mmap</summary><img src="img/零拷贝& mmap.png"  alt="零拷贝& mmap" /></details>
<details><summary>tcp</summary><img src="img/tcp.png"  alt="tcp" /></details>
<details><summary>分布式事务</summary><img src="img/分布式事务.png"  alt="分布式事务" /></details>
<details><summary>Iinux</summary><img src="img/Iinux.png"  alt="Iinux" /></details>
<details><summary>CMS</summary><img src="img/CMS.png"  alt="CMS" /></details>
<details><summary>多线程</summary><img src="img/多线程.png"  alt="多线程" /></details>
<details><summary>秒杀架构</summary><img src="img/秒杀架构.png"  alt="秒杀架构" /></details>
<details><summary>算法</summary><img src="img/算法.png"  alt="算法" /></details>
<details><summary>kafka</summary><img src="img/kafka.png"  alt="kafka" /></details>
<details><summary>API设计</summary><img src="img/API设计.png"  alt="API设计" /></details>
<details><summary>Java队列</summary><img src="img/Java队列.png"  alt="Java队列" /></details>


 在我准备面试的过程中,深刻的思考了如何才能更好更快速的做知识积累.我本人是个记忆力不强的人,看过的东西很容易忘,倒不是理解能力差,而是记住了,看懂了,过了一段时间对于一些细节模糊了, 以至于慢慢的只能对这些曾经熟悉精通的知识成为路人. 我把这种现象称为: 熟悉的陌生知识.

 实际上, 一时理解这些知识不难, 难在于长期理解.

 我在复习过程中,看了很多面经, 知识图谱等. 自己把这些知识放在标签栏里,放在有道笔记里,认为我记住了这些知识在哪里就可以了.我可以回头再看.

 可是我发现,一,别人整理的 不会再看.二.再看发现之前白看了.没有印象.

 后来和同学学习到使用 xmind 整理知识. 把是指归纳分类, 作为自己的笔记, 这些笔记里有别人的理解,也有我的理解.同时更多的是把之前琐碎的几篇文章才能说清楚的问题,放到了一个图里,一来方便,可以多次复习. 二来, 有了这颗归纳的树状图,真的记忆起来更加容易.

 希望读者也能总结自己的学习方法.

以下是面经.(Java 两年经验 ,前公司滴滴, 工作内容: 云计算管控层)

 笔者在面过 猿辅导,去哪儿,旷视, 陌陌,头条, 阿里, 快手, 美团, 腾讯之后,除了收获一大堆面试问题,还思考到如何成为面试官眼中的"爱技术,爱思考,靠谱,有潜力候选人的"一些"套路".

### 1. 面试问题(Java 后端)

#### 猿辅导
     1.八皇后问题
     2.求二叉树的最长距离(任意两个节点的路径 中最长的)
     3.lru 算法的实现
     4.设计一个数据结构 满足 put 和 getMedium(中位数)两个方法.
        (时间复杂度分析, getMedium 在常数,n,log n 时间复杂度返回如何实现)
     5.rabbitmq 脑裂问题,rabbitmq 延迟队列实现, rabbitmq高可用策略
        (因为项目中用到了 rabbitmq 和他们技术选型出现了重叠,问了这个问题)
     6. 死磕项目细节其中包括:
        设计方案时有没有比较多种方案,为什么选这个方案?
        你个人最有成就感,最有挑战性的 工作是哪一个?

     思考:
     1. 猿辅导问的算法题属于 leetcode easy, medium 级别的,基本不会太难


#### 旷视(Python)
       1. Python 如何实现多线程/多进程编程
       2. Python GIL 锁是什么?为什么会出现 GIL
       3. python 协程有么有用过? 有哪些常见的协程库,介绍一下
       4. python 装饰器如何实现,原理,常见使用场景?
       5. python 一堆我没听见的库,有没有用过.(我没记下来)
       6. 给你一个 Linux 路径,求其最简化的路径,例如(/a/b/.. -> /a,  a/b/./. -> a/b等)
       7. 给你一台 16 核, 32G 的机器, 无限空间大的分布式存储. 对1 个 16P 大小的文本文件进行排序.
           文件每行一条记录, 空格分割例如
           key1
           key2
       8. 介绍一下什么是外部排序

      思考:
      1. 旷视的这位面试官 和我死磕 python. 一点项目经历没问.
      2. 除了 leetcode 也要多看看高并发,大数据相关的 系统设计题.
#### 去哪儿(Java)
      1. 为什么使用 MQ, MQ 如何选型, 消息可靠性如何保证, 如何保证幂等
      2. 用过 dubbo吗? 设计一个 rpc 框架.
      3. 介绍一下 https
      4. 数据库线程池, http 连接池有没有深入看过源码?介绍一下.(项目里用得到了 http client)
      5. 给你十亿条数据,如何最快的添加到数据库中
      6. 分布式锁的技术选型, 实现原理, 优劣势比较, zookeeper 的一致性协议原理
      7. java 线程同步的几种方式, countdownlatch 和 栅栏的区别
      8. synchronized和 aqs 如何实现可重入锁

#### 陌陌
      1.分布式锁的实现方案比较,为什么选择 zookeeper, zookeeper 一致性协议原理
      2.一致性 Hash 原理,实现,项目中是如何使用一致性 Hash 的,引入了多少虚拟节点?
      3.java synchronized和 AQS的原理,区别
      4. redis 有序列表
      5. redis 高可用架构是什么? codis 和 redis cluster 分片的区别
      6. 两个线程如何交替打印 0到99

#### 头条(Go)
      1. 给你一个 Linux 路径,求其最简化的路径,例如(/a/b/.. -> /a,  a/b/./. -> a/b等) 和旷视问重了
      2. top-k
      3. 实现前缀树
      4. 实现python装饰器.方法实现,和类实现, 带参数和不带参数.以及对装饰器的思考
      5. 如何实现对 多机房,多机架 之前的网络健康情况监控.
      6. 如何理解进程上下文切换, 进程地址空间,为什么需要进程地址空间, 系统调用实现原理, top 命令介绍.

#### 阿里
      1. mq 消息可靠性,幂等如何保证
      2. 分布式锁的实现方案比较,为什么选择 zookeeper, zookeeper 一致性协议原理
      3. 线程池参数,阻塞队列实现.
      4. 一致性 Hash解决什么问题, 如何实现? 虚拟节点的作用?
      5. Java 锁的实现方式, 比较? AQS实现原理?公平非公平实现原理?
      6. CAS 实现原理
      7. volatile 实现原理, 单例模式
      8. java 内存模型, gc 调优的经历. cms gc 的几个阶段, 为什么会出现 stop the world. 常见可优化参数有哪些.
        为什么需要优化 gc, gc 会导致什么问题.
      9. mysql 事务隔离级别. mvcc 实现原理
      10. mysql 索引原理. 为什么使用 B+树. 及何时无法使用索引?
      11. mysql 架构, 引擎层和 server层 各自负责什么.
      12. hashmap 及 concurrenthashmap 实现原理
      13. Spring aop原理，如何定义新的spring xml 标签
      14. 合并两个有序链表
      15. 如何设计一个 大型活动的安保系统(开放题)
      16. 你平常都在哪些论坛上学习?
      17. 如何学习一门未知的技术?

      思考:
      阿里面试官 虽然不面算法,但是面试考察点全方位打击,从浅入深,揪住不放,直到你不会为止.
      是收获最多的面试,也是感受到自己差距的面试.



#### 快手
      1. 线程池实现原理,如何调优
      2. 如何实现一个延迟队列
      3. mysql 索引
      4. mysql 事务隔离级别
      5. java 锁和常见线程同步方式
      6. zookeeper 分布式实现方式及优劣,如何避免 多个客户端同时获取到锁?
      7. 求二叉树两个节点的共同节点
      8. 求二叉树的深度(非递归)
      9. java 集合常见类及原理
      10. tcc 原理
      11. netty 的请求处理流程.线程模型

#### 美团
      1. HashMap 的实现原理?扩容原理? 为什么 jdk 8修改了冲突链表的插入位置
      2. mysql 的高可用架构.主从同步过程.
      3. http 和rpc 调用的区别
      4. redis 如何用单线程支撑高并发, redis 的常见使用场景
      5. mq 如何选型. 为什么用 mq
      6. 一致性 Hash 原理
      7. 美团外卖的支付 ,要求在 15 分钟内取消未支付的订单. 如何实现
      8. 打印 * 星号的等腰三角形
      9. 项目的全链路架构, 有没有单点问题,解决单点问题有哪些常见的方案.
      10. 项目中有哪些可以衡量工作产出的指标.
      11. 说一下你负责的 最复杂,参与人数最多,周期对长.的项目是如何推进的
      12. 你认为自己的优势,劣势在哪里.
      13. 你对未来的职业规划,你期望的工作内容,方向是什么?


#### 腾讯(Java)
       1.如何在物理机和容器中获取 cpu 核数,如何设置线程数, 如何主动触发 GC
       2.一致性 Hash, Hash 的作用, 为什么叫一致性 Hash,一致性体现在哪里.
          HashMap中还可以使用什么方式处理 Hash 冲突
       3.线程池参数,优化,原理
       4.实现一个功能:
         cat /usr/local/*.log|grep tencent
         1. 并发 IO
         2. 30 s 内必须返回结果
       5. 如何理解 Future模式?java 的实现原理
       6. Java 阻塞队列实现原理
       7.  java 锁 volatile 实现原理
       8. mysql 索引原理,事务隔离级别, mysql 死锁的场景会有哪些, 内部如何检测死锁的?
       9. java 线程同步共有哪几种工具?
       10. 你认为 java 设计得比较优秀的地方有哪些?
       11. 如何理解面向对象设计,能用你看过得开源代码或者实际项目介绍一下吗?
       12. java 类加载器的原理及实际使用场景.
       13. java 内存模型, 虚拟机栈默认大小.
       14. 说一下高可用架构的常见解决思路

       思考:
       腾讯一面面试官考察点非常深入,要求你具有归纳能力.例如分布式中常见的负载策略,
       分布式中数据同步备份的常见方案.线程同步的几种方式等等.
       而且在你回答之后能继续深入逼问.
       不像其他面试官抛出来问题,他就听你吹. 你能吹多少,他就认为你会多少.

### 思考
   1. 手撕算法需要准备,面试之前保证刷够 100 题,及部分设计题.

   2. 无论会不会,一定不能慌.无论会不会,一定要和面试官确认自己的理解是不是正确,这道题应该如何思考? 避免跑偏

   3. 面试重点在于沟通.

       3.1 强行总结结论

         一定要有条理性的和面试官沟通. 避免东一笤帚,西一扫帚.最好提前想好一些结论,重复几遍.这样面试官可能直接用你的"结论"来 写面试经过,结论,评价等. 说完一件事,最好有条理性的结论,让面试官印象深刻. 即使强行 1,2,3的划重点结论也比戛然而止强.

       3.2 优雅的中断当前问题,只在检查点退出讨论,响应面试官的中断

         当面试官出现了疑问,抛出了问题,中断你的回答,一定不要一味的回答,立即响应,把握自己的节奏,先面试官征求意见,能否把剩下的说完.继续快速的说完,记得总结结论
        求同存异,避免争论

         面试官没有你熟悉你的项目,你的经历. 说,听,讨论. 三个阶段都会存在沟通信息的损失. 给面试官讲清楚, 让他理解,认同你可能很难. 但是如果出现争论,会降低对你的好感,降低沟通效率.所以你有责任及时的终止争论.可以使用一下技巧:

            1. 重申 上下文, 目的, 现状, 背景, 利弊抉择.
            2. 坦诚的承认这块我们的设计,实现并不是完美的.甚至做得不好.我们已经提出了哪些优化点(提出了解决方案).
            但是优先级并不是很高(优先级是最好的甩锅方式).当初由于更专注于业务目标.技术前瞻性做得不足.你的意见确实一针见血,
            这个问题让我们头疼了很久.
            3. "这块确实比较复杂,咱们总结一下,细化一下分歧再讨论" 面试官一般不会拒绝,面试方向主动权重新由你掌握.(要有主动权意识)
            4. 细化分歧过程中, 其实就是取得共识, 某些细枝末节的争论,直接和面试官解释,忽略掉即可. 把你们的共识摆出来.然后说:
            "咱们的分歧主要是什么什么,其实是我每说清楚,再针对面试官疑问解释一下,或者甩锅,我们想优化,因为优先级.我们想这么做,
            但是由于时间来不及,或者当时 XXX,没有这么做.不过后来我们确实吃了亏,算是技术债".
            (承认 low 没有问题,强项装逼不服输才是最二百五的)


### 面试三千问


#### 简历重要吗? 随便写行不行
     简历一定要认真写.面试官抛出的问题中,除了常见的高频面试题,就是简历中你写的东西.要保证简历中写的东西,
     透彻理解! 无论写的是了解,还是精通都要精通. 否则别写
     我认为不用写的
        1.不熟悉的,仅仅是知晓的.
        2.在学校整的东西,没啥知名度就不要写了
        3.github 要有,但是我没有被问过github 中的项目

#### 项目经历问吗?
     项目经历一般是 面试必问的,重点问的. 所以第一步要优先发掘自己项目中的亮点, 把自己做的工作清晰的写出来.
      自我介绍阶段重点介绍应该也是自己的项目经历,这时最好自己提前准备一份演讲稿把自己的项目亮点说出来.
      多练几遍.避免不过脑子,黄河决堤式回答,想到哪里说哪里.


#### 常见高频问题呢?
     java 锁,线程同步,Juc 包.线程池
     内存模型,gc 调优
     mysql 索引,锁,事务隔离级别.
     常见分布式高可用架构 redis, mysql, zk, mq等. 数据同步,数据分片,数据备份等

#### 需要刷题吗?
     阿里一般不会问太多算法题.
     但是至少一半以上公司都会手撕算法.  把leetcode 各个类型的题都刷十道以上基本没太大问题. hard题一般不会问.
     如果自己面试表现非常好,但是因为算法题被刷掉是不是会很遗憾呢?
      算法题能扩展一个人的思路,还是有用的.也锻炼一个人编码能力. 个人建议白板算法用 python 非常简洁.更聚焦解题思路

     如果自己面试表现特别好,职位匹配度非常高. 算法题是可以防水的,会挑简单题问. 目的就是 留下你,怕你答不上来,避免尴尬

     但是自己面试比较差, 算法题答得特别好,会不会扭转面试结果呢? 基本不会, 手撕算法只是辅助.项目经历和基础面试题是核心.

#### 面试结果可以问吗?
     如果没有面试到 hr,或者 终面面试官没有明确 hr 会联系,我基本都会问. 或者问一下自己的不足. 一般都会告诉自己.
     另外, 手撕算法OK,也会被刷掉. 我在陌陌就是 手撕算法非常完美,结果还是挂了.


### 一般几轮面试?
    不算 hr ,基本都是三轮. 但如果二轮面试官开始扯虚的,和你介绍项目,问你职业规划 也许二面就是终面. 不清楚就问一下面试官.


#### 平时工作划水, 面试临时抱佛脚行不行?
    不行
    当面试官逼问项目细节时, 如果平时没有对细节特别熟悉,做事马马虎虎,技术深度不够,例如 技术选型为什么这么做,其他方案?优劣势是什么?
     如果没有调研,面试时,很快会露出马脚.
    如果对项目的整体架构不熟悉,只熟悉自己的模块,也会可能被面试官问到关联的模块,项目如果自己不熟悉,马上就会支支吾吾.如果你回答,这块
    不是我负责的,我不太熟悉,就会让面试官对你产生 没有大局观,主动意识不够的狐疑.评价时会被评"只能完成自己模块内的工作,对系统的全局
    没有了解,主动意识不强.自我驱动意识差"
    工作时,可能仅仅聚焦业务,对于项目中应用的技术关注不足. 面试时候就会被面试官揪住.如果当时不思考清晰,并且面试前没有意识到这块技术
    风险, 就会给面试带来很大风险.美团面试官曾问我,介绍一个你主要负责的 参与方最多,周期最长,最复杂的一个项目如何推进的? 如果平时工
    作不积极,不主动思考,面试被摊上这么一个问题.基本上哑口无言. (我就目瞪口呆了)


#### 仅仅看博客,把高频面试题搞懂行不行? (问题驱动式准备面试)
    这是必须要做的事情.但是仅仅做到这些还远远不够
    例如:
    阿里面试官问:gc 为什么一定要 stop the world? 一般博客没有给出明确清晰直观的原因.

    一致性 Hash 如何实现? 手撕一下.为什么叫一致性 hash,一致性体现在哪里? 一般博客没有.

    lru 算法手撕一下. 博客有,看一遍就能手撕了?

    redis 和 zk 分布式锁实现如何选型? 各自缺点,优势?项目使用时如何避免缺点带来的负面影响?

    如何基于 AQS实现获取锁的公平性非公平性?

    面试官甚至给你埋坑,故意说一个错误的,看你能否反驳.

    我之前被带坑过, 线程池问题
    面试官问:是先到 max size 还是先添加到阻塞队列?
    我说     阻塞队列满了才会继续创建线程到max size
    面试官:  是这样吗? 那么如果是无界队列岂不是永远无法到达 max size
    我心想:  是啊,有道理,我可能记错了.然后被面试官带偏了.

    所以结论是,光看懂记下来,不够,要深刻理解.时刻带着问题去学习.问题驱动式学习.
    最后你会发现,
    过了许久,你印象最深刻的还是自己当初提出来的疑问及其解决思路和答案.

    