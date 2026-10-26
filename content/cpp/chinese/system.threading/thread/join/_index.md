---
title: Join()
second_title: Aspose.Slides for C++ API 参考
description: 加入受管理的线程。如有必要，执行无限等待。
type: docs
weight: 196
url: /zh/system.threading/thread/join/
---
## Thread::Join() 方法

加入受管理的线程。如有必要，执行无限等待。

```cpp
void System::Threading::Thread::Join()
```
## Thread::Join(int) 方法

加入受管理的线程。执行有限等待。

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsTimeout | int | 以毫秒为单位的等待超时时间。 |

### 返回值

如果线程成功加入则返回 true，超时则返回 false。

## Thread::Join(TimeSpan) 方法

加入受管理的线程。执行有限等待。

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | 设置为等待线程终止的时间量的 [TimeSpan](../../../system/timespan/)。 |

### 返回值

如果线程成功加入则返回 true，超时则返回 false。

## 参见

* 类 [Thread](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)