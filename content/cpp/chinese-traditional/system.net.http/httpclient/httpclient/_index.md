---
title: HttpClient()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的實例。
type: docs
weight: 92
url: /zh-hant/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() 建構函式

建立新的實例。

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) 建構函式

建立新的實例。

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 用於發送請求的 HTTP 處理程式。 |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) 建構函式

建立新的實例。

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 用於發送請求的 HTTP 處理程式。 |
| disposeHandler | **bool** | 指示在釋放此實例時是否必須釋放處理程式的值。 |

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [HttpClient](../)
* 類別 [HttpMessageHandler](../../httpmessagehandler/)
* 命名空間 [System::Net::Http](../../)
* 函式庫 [Aspose.Slides](../../../)