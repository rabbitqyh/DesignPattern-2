Algorithm
=========
常用设计模式C++实现

###Singletion.h
单例模式
    单例模式实现，其中采用多种实现方案
    可以实现禁止外部创建，拷贝，和delete
    线程安全的两种实现方式：互斥量和程序加载时创建两种方式
    实现程序退出时自动调用垃圾工人去释放单例内存