---
title: BeginAcceptSocket()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 非同期の受け入れ操作を開始します。
type: docs
weight: 144
url: /ja/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期の受け入れ操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するために使用される、ユーザー提供データ。 |

### 戻り値

[IAsyncResult](../../../system/iasyncresult/) オブジェクトは、開始された非同期受け入れ操作を表します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [TcpListener](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)