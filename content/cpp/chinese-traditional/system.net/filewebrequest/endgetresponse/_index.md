---
title: EndGetResponse()
second_title: Aspose.Slides C++ API 參考文件
description: 等待指定資源的非同步請求完成。
type: docs
weight: 183
url: /zh-hant/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) 方法

等待指定資源的非同步請求完成。

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 代表資源之非同步請求的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 回傳值

Web 回應。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [WebResponse](../../webresponse/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [FileWebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)