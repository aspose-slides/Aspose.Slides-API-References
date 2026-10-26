---
title: EndGetHostAddresses()
second_title: Aspose.Slides for C++ API 參考
description: 等待指定的非同步操作完成，以建立新的 IPHostEntry-class 實例。
type: docs
weight: 144
url: /zh-hant/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的非同步操作完成，以建立新的 IPHostEntry-class 實例。

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 代表非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 回傳值

新建立的 IPHostEntry-class 實例。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPAddress](../../ipaddress/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Dns](../)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)