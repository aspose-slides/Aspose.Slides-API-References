---
title: Send()
second_title: Aspose.Slides for C++ API 参考
description: 发送指定的 HTTP 请求。
type: docs
weight: 118
url: /zh/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) 方法

发送指定的 HTTP 请求。

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | 必须发送的 HTTP 请求。 |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | 指示何时完成操作的值。 |

## 另请参阅

* 枚举 [HttpCompletionOption](../../httpcompletionoption/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [HttpResponseMessage](../../httpresponsemessage/)
* 类 [HttpRequestMessage](../../httprequestmessage/)
* 类 [HttpClient](../)
* 命名空间 [System::Net::Http](../../)
* 库 [Aspose.Slides](../../../)