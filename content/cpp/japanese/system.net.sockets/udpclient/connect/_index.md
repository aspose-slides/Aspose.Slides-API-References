---
title: Connect()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホストの指定されたポートへの接続を確立します。
type: docs
weight: 66
url: /ja/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) メソッド


指定されたホストの指定されたポートへの接続を確立します。

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 接続しようとしているリモート DNS ホストの名前です。 |
| port | **int32_t** | 通信しようとしているローカル ポート番号です。 |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) メソッド


指定されたアドレスのホストに、指定されたポートで接続を確立します。

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | データを送信するリモート ホストの[IPAddress](../../../system.net/ipaddress/)です。 |
| port | **int32_t** | 通信しようとしているローカル ポート番号です。 |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) メソッド


リモート エンドポイントへの接続を確立します。

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | UDP 接続をバインドするエンドポイントです。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [UdpClient](../)
* クラス [IPAddress](../../../system.net/ipaddress/)
* クラス [IPEndPoint](../../../system.net/ipendpoint/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)