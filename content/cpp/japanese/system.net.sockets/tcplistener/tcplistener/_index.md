---
title: TcpListener()
second_title: Aspose.Slides の C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 53
url: /ja/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | リスナーソケットをバインドしなければならないローカルエンドポイント。 |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | ローカルIPアドレス。 |
| port | **int32_t** | 待ち受けるポート番号。 |

## TcpListener::TcpListener(int32_t) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| port | **int32_t** | 待ち受けるポート番号。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPEndPoint](../../../system.net/ipendpoint/)
* クラス [TcpListener](../)
* クラス [IPAddress](../../../system.net/ipaddress/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)