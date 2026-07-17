---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API 参考
description: 将工作项添加到队列。
type: docs
weight: 1
url: /zh/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) 方法

将工作项添加到队列。

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 要执行的回调函数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 回调函数参数。 |

### 返回值

始终返回 true。

## 另请参见

* 类型定义 [WaitCallback](../../waitcallback/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [ThreadPoolImpl](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)