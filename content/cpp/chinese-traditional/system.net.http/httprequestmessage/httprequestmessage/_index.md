---
title: HttpRequestMessage()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的實例。
type: docs
weight: 131
url: /zh-hant/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() constructor

建立新的實例。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) constructor

建立新的實例。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP 方法。 |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 所請求資源的 URI。 |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) constructor

建立新的實例。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP 方法。 |
| requestUri | [String](../../../system/string/) | 所請求資源的 URI。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [HttpRequestMessage](../)
* 類別 [HttpMethod](../../httpmethod/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)