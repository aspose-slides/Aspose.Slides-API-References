---
title: WaitAny()
second_title: Aspose.Slides for C++ API 参考
description: 等待任意句柄触发。
type: docs
weight: 14
url: /zh/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) 方法


等待任意一个句柄触发。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |
| millisecondsTimeout | int | [Timeout](../../timeout/) 要等待的时间，单位为毫秒；-1 表示无限等待，0 表示检查后返回，正值表示超时。 |

### 返回值

如果有任意句柄触发则返回 True；如果超时则返回 false。

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) 方法


等待任意一个句柄触发。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) 表示要等待的毫秒数，或 [System::TimeSpan](../../../system/timespan/) 表示 -1 毫秒（无限期等待）。 |

### 返回值

如果有任意句柄触发则返回 True；如果超时则返回 false。

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) 方法


等待任意一个句柄触发。

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 要等待的句柄。 |

### 返回值

当 waitHandles 中的每个元素都收到信号时返回 True；否则方法永不返回。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [WaitHandle](../)
* 类 [TimeSpan](../../../system/timespan/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)