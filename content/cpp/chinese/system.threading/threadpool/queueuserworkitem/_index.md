---
title: QueueUserWorkItem()
second_title: Aspose.Slides C++ API 参考
description: 将工作项放入队列，该工作项由不带参数的回调表示。
type: docs
weight: 14
url: /zh/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) 方法


将工作项放入队列，该工作项由不带参数的回调表示。

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 用于作为作业的回调函数。 |

### 返回值

始终返回 true。

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) 方法


将工作项放入队列，该工作项由不带参数的回调表示。

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 用于作为作业的回调函数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 作业函数的参数。 |

### 返回值

始终返回 true。

## 另请参阅

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ThreadPool](../)
* 类 [Object](../../../system/object/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)