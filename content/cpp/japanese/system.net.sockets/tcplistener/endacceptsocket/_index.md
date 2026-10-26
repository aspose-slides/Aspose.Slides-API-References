---
title: EndAcceptSocket()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期受け入れ操作が完了するまで待機します。
type: docs
weight: 157
url: /ja/system.net.sockets/tcplistener/endacceptsocket/
---
## TcpListener::EndAcceptSocket(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期受け入れ操作が完了するまで待機します。

```cpp
System::SharedPtr<Socket> System::Net::Sockets::TcpListener::EndAcceptSocket(System::SharedPtr<IAsyncResult> asyncResult)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトは、非同期受け入れ操作を表します。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Socket](../../socket/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [TcpListener](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)