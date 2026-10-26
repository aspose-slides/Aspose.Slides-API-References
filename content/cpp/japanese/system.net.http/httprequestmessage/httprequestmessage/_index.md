---
title: HttpRequestMessage()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 131
url: /ja/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP メソッドです。 |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 要求されたリソースの URI です。 |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP メソッドです。 |
| requestUri | [String](../../../system/string/) | 要求されたリソースの URI です。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [HttpRequestMessage](../)
* クラス [HttpMethod](../../httpmethod/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Net::Http](../../)
* ライブラリ [Aspose.Slides](../../../)