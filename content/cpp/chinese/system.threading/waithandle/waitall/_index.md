---
title: WaitAll()
second_title: Aspose.Slides for C++ API 参考
description: 等待所有句柄触发。
type: docs
weight: 1
url: /zh/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) 方法

等待所有句柄触发。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |
| millisecondsTimeout | int | [Timeout](../../timeout/)等待的时间，以毫秒为单位；-1 表示无限等待，0 表示检查后返回，正值为超时。 |

### 返回值

如果所有句柄已触发则返回 true；如果超时则返回 false。

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) 方法

等待所有句柄触发。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |
| timeout | [TimeSpan](../../../system/timespan/) | 一个 [System::TimeSpan](../../../system/timespan/)，表示等待的毫秒数，或一个 [System::TimeSpan](../../../system/timespan/)，表示 -1 毫秒即无限等待。 |

### 返回值

如果所有句柄已触发则返回 true；如果超时则返回 false。

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) 方法

等待所有句柄触发。

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |

### 返回值

当 waitHandles 中的每个元素都已收到信号时返回 true；否则该方法永不返回。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)