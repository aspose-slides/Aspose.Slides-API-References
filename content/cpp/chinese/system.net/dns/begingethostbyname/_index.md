---
title: BeginGetHostByName()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的主机名发起异步操作以创建新的 IPHostEntry-class 实例。
type: docs
weight: 53
url: /zh/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起一个异步操作以使用指定的主机名创建新的 IPHostEntry 类实例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | 一个主机名。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时要调用的回调。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

一个代表已发起的异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [Dns](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)