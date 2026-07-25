---
title: UdpClient()
second_title: Aspose.Slides for C++ API リファレンス
description: UdpClient クラスの新しいインスタンスを初期化します。
type: docs
weight: 27
url: /ja/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() コンストラクタ

[UdpClient](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) コンストラクタ

[UdpClient](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | ソケットのアドレッシング方式を指定する値です。 |

## UdpClient::UdpClient(int32_t) コンストラクタ

[UdpClient](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | 通信に使用するローカルポート番号です。 |

## UdpClient::UdpClient(int32_t, AddressFamily) コンストラクタ

[UdpClient](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | 通信に使用するローカルポート番号です。 |
| family | [AddressFamily](../../addressfamily/) | ソケットのアドレッシング方式を指定する値です。 |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) コンストラクタ

[UdpClient](../) クラスの新しいインスタンスを初期化します。パラメーター local EP は、UDP 接続をバインドするローカルエンドポイントです。

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) コンストラクタ

[UdpClient](../) クラスの新しいインスタンスを作成し、指定されたリモートホストに指定ポートで接続します。

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 接続先のリモート DNS ホストの名前です。 |
| port | **int32_t** | 通信に使用するローカルポート番号です。 |

## 参照

* 列挙体 [AddressFamily](../../addressfamily/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [UdpClient](../)
* クラス [IPEndPoint](../../../system.net/ipendpoint/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)