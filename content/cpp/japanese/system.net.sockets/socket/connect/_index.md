---
title: Connect()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリモートエンドポイントへの接続を確立します。
type: docs
weight: 560
url: /ja/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) メソッド

指定されたリモートエンドポイントへの接続を確立します。

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) メソッド

指定されたリモートエンドポイントへの接続を確立します。

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | リモートホストのIPアドレス。 |
| port | **int32_t** | リモートホストのポート番号。 |

## Socket::Connect(String, int32_t) メソッド

指定されたリモートエンドポイントへの接続を確立します。

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | リモートホスト名。 |
| port | **int32_t** | リモートホストのポート番号。 |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) メソッド

指定されたリモートエンドポイントへの接続を確立します。

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | リモートホストのIPアドレス。 |
| port | **int32_t** | リモートホストのポート番号。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [EndPoint](../../../system.net/endpoint/)
* クラス [Socket](../)
* クラス [IPAddress](../../../system.net/ipaddress/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)