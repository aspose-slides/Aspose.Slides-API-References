---
title: HttpMessageInvoker()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新實例。
type: docs
weight: 1
url: /zh-hant/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) 建構函式


建立一個新實例。

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 用於發送請求的 HTTP 處理程式。 |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) 建構函式


建立一個新實例。

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 用於發送請求的 HTTP 處理程式。 |
| disposeHandler | **bool** | 指示在處置此實例時是否必須釋放處理程式的值。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [HttpMessageHandler](../../httpmessagehandler/)
* 類別 [HttpMessageInvoker](../)
* 命名空間 [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)