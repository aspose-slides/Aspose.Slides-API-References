---
title: WaitOne()
second_title: Aspose.Slides for C++ API 参考
description: 锁定信号量。如果有必要，执行无限等待。
type: docs
weight: 40
url: /zh/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() 方法

锁定信号量。如果有必要，执行无限等待。

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### 返回值

始终返回 true，因为在信号量被锁定之前不会返回。

## Semaphore::WaitOne(int) 方法

锁定信号量。如果有必要，执行等待。

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsTimeout | int | 以毫秒为单位的等待超时时间。 |

### 返回值

如果信号量已被锁定则返回 true；如果超时则返回 false。

## 另请参见

* 类 [Semaphore](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)