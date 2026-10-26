---
title: Send()
second_title: Aspose.Slides for C++ API 參考
description: 發送指定的 HTTP 請求。
type: docs
weight: 118
url: /zh-hant/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) 方法


發送指定的 HTTP 請求。

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | 必須發送的 HTTP 請求。 |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | 指示何時完成操作的值。 |

## 另請參閱

* Enum [HttpCompletionOption](../../httpcompletionoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponseMessage](../../httpresponsemessage/)
* Class [HttpRequestMessage](../../httprequestmessage/)
* Class [HttpClient](../)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)