---
title: EndResolve()
second_title: Aspose.Slides for C++ API 參考文件
description: 等待指定的非同步操作完成，以建立新的 IPHostEntry-class 實例。
type: docs
weight: 170
url: /zh-hant/system.net/dns/endresolve/
---
## Dns::EndResolve(System::SharedPtr\<IAsyncResult\>) 方法


等待指定的非同步操作完成，以建立新的 IPHostEntry-class 實例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 代表非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 返回值

新建立的 IPHostEntry-class 實例。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPHostEntry](../../iphostentry/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Dns](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)