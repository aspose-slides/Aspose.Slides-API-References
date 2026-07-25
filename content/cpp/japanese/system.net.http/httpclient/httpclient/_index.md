---
title: HttpClient()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 92
url: /ja/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | リクエスト送信に使用される HTTP ハンドラです。 |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | リクエスト送信に使用される HTTP ハンドラです。 |
| disposeHandler | **bool** | ハンドラをこのインスタンスが破棄されるときに破棄するかどうかを示す値です。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [HttpClient](../)
* クラス [HttpMessageHandler](../../httpmessagehandler/)
* 名前空間 [System::Net::Http](../../)
* ライブラリ [Aspose.Slides](../../../)