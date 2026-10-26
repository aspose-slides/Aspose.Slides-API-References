---
title: EndGetHostByName()
second_title: Aspose.Slides for C++ API 参考
description: 等待指定的异步操作完成，以创建新的 IPHostEntry-class 实例。
type: docs
weight: 66
url: /zh/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) 方法


等待指定的异步操作完成，以创建新的 IPHostEntry-class 实例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。 |

### 返回值

新创建的 IPHostEntry-class 实例。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPHostEntry](../../iphostentry/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Dns](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)