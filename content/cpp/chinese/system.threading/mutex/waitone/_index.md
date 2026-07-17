---
title: WaitOne()
second_title: Aspose.Slides for C++ API 参考
description: 锁定互斥体。如果需要，执行无限等待。
type: docs
weight: 53
url: /zh/system.threading/mutex/waitone/
---
## Mutex::WaitOne() 方法

锁定互斥体。如果需要，执行无限等待。

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### 返回值

始终返回 true，因为在互斥体被锁定之前不会返回。

## Mutex::WaitOne(int) 方法

锁定互斥体。如果需要，执行等待。

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsTimeout | int | 以毫秒为单位的等待超时。 |

### 返回值

如果互斥体已锁定则返回 true；如果超时则返回 false。

## Mutex::WaitOne(TimeSpan) 方法

锁定互斥体。如果需要，执行等待。

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | 一个 [System::TimeSpan](../../../system/timespan/)，表示等待的毫秒数，或者一个 [System::TimeSpan](../../../system/timespan/)，表示 -1 毫秒，以无限期等待。 |

### 返回值

如果互斥体已锁定则返回 true；如果超时则返回 false。

## 另请参见

* 类 [Mutex](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)