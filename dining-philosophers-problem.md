# 哲学家就餐问题

\*\*\*\*[**哲学家就餐问题**](https://zh.wikipedia.org/wiki/%E5%93%B2%E5%AD%A6%E5%AE%B6%E5%B0%B1%E9%A4%90%E9%97%AE%E9%A2%98)（英语：Dining philosophers problem）是在[计算机科学](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A7%91%E5%AD%A6)中的一个经典问题，用来演示在[并发计算](https://zh.wikipedia.org/wiki/Concurrent_computing)中[多线程](https://zh.wikipedia.org/wiki/%E5%A4%9A%E7%BA%BF%E7%A8%8B)[同步](https://zh.wikipedia.org/wiki/%E5%90%8C%E6%AD%A5)（Synchronization）时产生的问题。

在1971年，著名的计算机科学家[艾兹格·迪科斯彻](https://zh.wikipedia.org/wiki/%E8%89%BE%E5%85%B9%E6%A0%BC%C2%B7%E8%BF%AA%E7%A7%91%E6%96%AF%E5%BD%BB)提出了一个同步问题，即假设有五台计算机都试图访问五份共享的磁带驱动器。稍后，这个问题被[托尼·霍尔](https://zh.wikipedia.org/wiki/%E6%89%98%E5%B0%BC%C2%B7%E9%9C%8D%E7%88%BE)重新表述为哲学家就餐问题。这个问题可以用来解释[死锁](https://zh.wikipedia.org/wiki/%E6%AD%BB%E7%B5%90)和资源耗尽。

![&#x54F2;&#x5B66;&#x5BB6;&#x5C31;&#x9910;&#x95EE;&#x9898;&#x56FE;&#x89E3;](.gitbook/assets/image%20%281%29.png)

拓展阅读 - 死锁的四个条件:

* **禁止抢占**（no preemption）：系统资源不能被强制从一个进程中退出。
* **持有和等待**（hold and wait）：一个进程可以在等待时持有系统资源。
* **互斥**（mutual exclusion）：资源只能同时分配给一个行程，无法多个行程共享。
* **循环等待**（circular waiting）：一系列进程互相持有其他进程所需要的资源。

死锁只有在四个条件同时满足时发生，预防死锁必须至少破坏其中一项。

