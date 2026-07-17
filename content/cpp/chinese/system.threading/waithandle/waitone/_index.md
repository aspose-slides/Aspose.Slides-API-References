---
title: WaitOne()
second_title: Aspose.Slides C++ API 参考
description: 等待句柄触发，时间无限。
type: docs
weight: 27
url: /zh/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() 方法

等待句柄触发，时间无限。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### 返回值

始终返回 true，因为不会发生超时。

## WaitHandle::WaitOne(int) 方法

等待句柄触发。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) 等待的时间，以毫秒为单位；-1 表示无限等待，0 表示检查后返回，正值表示超时。 |

### 返回值

如果句柄已触发则返回 true，如果超时则返回 false。

## WaitHandle::WaitOne(TimeSpan) 方法

等待句柄触发。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) 表示要等待的毫秒数，或 [System::TimeSpan](../../../system/timespan/) 表示 -1 毫秒的无限等待。 |

### 返回值

如果句柄已触发则返回 true，如果超时则返回 false。

## WaitHandle::WaitOne(int, bool) 方法

等待句柄触发。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) 等待的时间，以毫秒为单位；-1 表示无限等待，0 表示检查后返回，正值表示超时。 |
| exitContext | **bool** | 如果为 true，则在等待之前应释放对句柄的锁。 |

### 返回值

如果句柄已触发则返回 true，如果超时则返回 false。

## 另请参见

* 类 [WaitHandle](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)