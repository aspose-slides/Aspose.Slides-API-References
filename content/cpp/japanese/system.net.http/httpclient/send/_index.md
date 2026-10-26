---
title: Send()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された HTTP リクエストを送信します。
type: docs
weight: 118
url: /ja/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) メソッド

指定された HTTP リクエストを送信します。

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | 送信すべき HTTP リクエストです。 |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | 操作を完了するタイミングを示す値です。 |

## 参照

* Enum [HttpCompletionOption](../../httpcompletionoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [HttpResponseMessage](../../httpresponsemessage/)
* クラス [HttpRequestMessage](../../httprequestmessage/)
* クラス [HttpClient](../)
* 名前空間 [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)