---
title: EndGetHostByName()
second_title: Aspose.Slides for C++ API 參考
description: 等待指定的非同步操作完成，以建立新的 IPHostEntry-class 實例。
type: docs
weight: 66
url: /zh-hant/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的非同步操作完成，以建立新的 IPHostEntry 類別實例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 傳回值

新建立的 IPHostEntry 類別實例。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPHostEntry](../../iphostentry/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Dns](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)