---
title: BeginGetHostAddresses()
second_title: Aspose.Slides C++ API 参考
description: 启动一个异步操作，以使用包含主机名或 IP 地址的指定字符串创建一个新的 IPHostEntry-class 实例。
type: docs
weight: 131
url: /zh/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) 方法

启动一个异步操作，以使用包含主机名或 IP 地址的指定字符串创建一个新的 IPHostEntry 类实例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 一个包含主机名或 IP 地址的字符串。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示已启动的异步操作。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [Dns](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)