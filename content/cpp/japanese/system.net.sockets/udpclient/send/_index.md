---
title: Send()
second_title: Aspose.Slides for C++ API リファレンス
description: リモート エンドポイントのホストに UDP データグラムを送信します。
type: docs
weight: 79
url: /ja/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method

リモート エンドポイントのホストに UDP データグラムを送信します。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するための [Byte](../../../system/byte/) 型の配列 |
| bytes | **int32_t** | データグラムのバイト数 |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | データグラムを送信するホストとポートを表す [IPEndPoint](../../../system.net/ipendpoint/) |

### 戻り値

送信されたバイト数

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method

指定されたリモートホストの指定ポートに UDP データグラムを送信します。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するための [Byte](../../../system/byte/) 型の配列 |
| bytes | **int32_t** | データグラムのバイト数 |
| hostname | [String](../../../system/string/) | リモートホストの名前 |
| port | **int32_t** | リモートポート番号 |

### 戻り値

送信されたバイト数

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method

リモートホストに UDP データグラムを送信します。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するための [Byte](../../../system/byte/) 型の配列 |
| bytes | **int32_t** | データグラムのバイト数 |

### 戻り値

送信されたバイト数

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)