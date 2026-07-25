---
title: Send()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリクエストを送信します。
type: docs
weight: 27
url: /ja/system.net.http/httpclienthandler/send/
---
## HttpClientHandler::Send(System::SharedPtr\<HttpRequestMessage\>) メソッド

指定されたリクエストを送信します。

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClientHandler::Send(System::SharedPtr<HttpRequestMessage> request) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | 送信するリクエスト。 |

### 戻り値

HTTP レスポンス メッセージ。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [HttpResponseMessage](../../httpresponsemessage/)
* クラス [HttpRequestMessage](../../httprequestmessage/)
* クラス [HttpClientHandler](../)
* 名前空間 [System::Net::Http](../../)
* ライブラリ [Aspose.Slides](../../../)