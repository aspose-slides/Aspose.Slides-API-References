---
title: EndGetHostAddresses()
second_title: Aspose.Slides C++ API 参考
description: 等待指定的异步操作完成，以创建一个新的 IPHostEntry-class 实例。
type: docs
weight: 144
url: /zh/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的异步操作完成，以创建一个新的 IPHostEntry-class 实例。

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示异步操作。 |

### 返回值

一个新创建的 IPHostEntry-class 实例。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPAddress](../../ipaddress/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Dns](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)