---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API 參考
description: 等待直到指定的資源非同步請求完成。
type: docs
weight: 287
url: /zh-hant/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) 方法

等待直到指定的資源非同步請求完成。

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示資源非同步請求的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 返回值

網路回應。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)