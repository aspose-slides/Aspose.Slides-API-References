---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期の受け入れ操作を開始します。
type: docs
weight: 170
url: /ja/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期の受け入れ操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 非同期接続操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

[IAsyncResult](../../../system/iasyncresult/) オブジェクトで、開始された非同期受け入れ操作を表します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)