---
title: BeginResolve()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的主机名发起异步操作以创建新的 IPHostEntry-class 实例。
type: docs
weight: 157
url: /zh/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) method

发起一个异步操作，以使用指定的主机名创建新的 IPHostEntry-class 实例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | 用于创建 [IPHostEntry](../../iphostentry/) 类的新实例的主机名。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时调用的回调。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

表示已启动的异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [Dns](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)