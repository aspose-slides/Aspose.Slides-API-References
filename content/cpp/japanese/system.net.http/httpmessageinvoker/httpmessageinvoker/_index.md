---
title: HttpMessageInvoker()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) コンストラクタ


新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | リクエストの送信に使用される HTTP ハンドラです。 |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) コンストラクタ


新しいインスタンスを作成します。

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | リクエストの送信に使用される HTTP ハンドラです。 |
| disposeHandler | **bool** | このインスタンスが破棄される際にハンドラを破棄すべきかどうかを示す値です。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [HttpMessageHandler](../../httpmessagehandler/)
* クラス [HttpMessageInvoker](../)
* 名前空間 [System::Net::Http](../../)
* ライブラリ [Aspose.Slides](../../../)