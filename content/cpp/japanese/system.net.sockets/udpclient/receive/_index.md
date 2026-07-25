---
title: Receive()
second_title: Aspose.Slides for C++ API リファレンス
description: サーバーから送信されたデータグラムを返します。
type: docs
weight: 92
url: /ja/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) method

サーバーから送信されたデータグラムを返します。

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | データが送信されたリモートホストを表す[IPEndPoint](../../../system.net/ipendpoint/)です。 |

### 戻り値

受信したデータが割り当てられるバイト配列です。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPEndPoint](../../../system.net/ipendpoint/)
* クラス [UdpClient](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)