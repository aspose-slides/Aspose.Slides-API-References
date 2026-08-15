---
title: EndGetResponse()
second_title: Aspose.Slides C++ API 參考
description: 等待指定的資源非同步請求完成。
type: docs
weight: 508
url: /zh-hant/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) 方法


等待指定的資源非同步請求完成。

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示資源非同步請求的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 返回值

Web 回應。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [WebResponse](../../webresponse/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [HttpWebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)