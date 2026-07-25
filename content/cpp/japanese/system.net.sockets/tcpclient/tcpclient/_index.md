---
title: TcpClient()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 235
url: /ja/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | ソケットがバインドされるエンドポイント。 |

## TcpClient::TcpClient() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) コンストラクト

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | アドレスファミリ。 |

## TcpClient::TcpClient(String, int32_t) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 接続先のリモートホスト名。 |
| port | **int32_t** | 接続先リモートホストのポート。 |

## 参照

* 列挙型 [AddressFamily](../../addressfamily/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPEndPoint](../../../system.net/ipendpoint/)
* クラス [TcpClient](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)