---
title: EndAcceptTcpClient()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期受け入れ操作が完了するまで待機します。
type: docs
weight: 183
url: /ja/system.net.sockets/tcplistener/endaccepttcpclient/
---
## TcpListener::EndAcceptTcpClient(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期受け入れ操作が完了するまで待機します。

```cpp
System::SharedPtr<TcpClient> System::Net::Sockets::TcpListener::EndAcceptTcpClient(System::SharedPtr<IAsyncResult> asyncResult)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 非同期受け入れ操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [TcpClient](../../tcpclient/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [TcpListener](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)