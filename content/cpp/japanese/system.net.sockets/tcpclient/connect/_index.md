---
title: Connect()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリモートホストへの接続を確立します。
type: docs
weight: 248
url: /ja/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) メソッド

指定されたリモートホストへの接続を確立します。

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 接続先のリモートホスト名。 |
| port | **int32_t** | 接続先リモートホストのポート。 |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) メソッド

指定されたリモートホストへの接続を確立します。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | リモートホストの IP アドレス。 |
| port | **int32_t** | 接続先リモートホストのポート。 |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) メソッド

指定されたリモートホストへの接続を確立します。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 接続先のリモートホスト。 |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) メソッド

指定されたリモートホストへの接続を確立します。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | リモートホストの IP アドレス一覧。 |
| port | **int32_t** | 接続先リモートホストのポート。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [TcpClient](../)
* クラス [IPAddress](../../../system.net/ipaddress/)
* クラス [IPEndPoint](../../../system.net/ipendpoint/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)