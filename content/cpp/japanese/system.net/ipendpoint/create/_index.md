---
title: Create()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたソケット アドレスを使用して、EndPoint クラスの新しいインスタンスを作成します。
type: docs
weight: 92
url: /ja/system.net/ipendpoint/create/
---
## IPEndPoint::Create(System::SharedPtr\<SocketAddress\>) method


指定されたソケット アドレスを使用して、[EndPoint](../../endpoint/) クラスの新しいインスタンスを作成します。

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| socketAddress | [System::SharedPtr](../../../system/sharedptr/)\<[SocketAddress](../../socketaddress/)\> | 新しいインスタンスの初期化に使用されるソケット アドレスです。 |

### 戻り値

新しく作成された EndPoint クラスのインスタンスです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [EndPoint](../../endpoint/)
* クラス [SocketAddress](../../socketaddress/)
* クラス [IPEndPoint](../)
* 名前空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)