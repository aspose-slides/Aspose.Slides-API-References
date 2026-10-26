---
title: Send()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 UDP 資料報傳送至遠端端點的主機。
type: docs
weight: 79
url: /zh-hant/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method

將 UDP 資料報傳送至遠端端點的主機。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的 [Byte](../../../system/byte/) 陣列 |
| bytes | **int32_t** | 資料報中的位元組數量 |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 表示要傳送資料報的主機與埠的 [IPEndPoint](../../../system.net/ipendpoint/) |

### 傳回值

傳送的位元組數量。

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method

將 UDP 資料報傳送至指定遠端主機的指定埠。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的 [Byte](../../../system/byte/) 陣列 |
| bytes | **int32_t** | 資料報中的位元組數量 |
| hostname | [String](../../../system/string/) | 遠端主機的名稱 |
| port | **int32_t** | 遠端埠號 |

### 傳回值

傳送的位元組數量。

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method

將 UDP 資料報傳送至遠端主機。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的 [Byte](../../../system/byte/) 陣列 |
| bytes | **int32_t** | 資料報中的位元組數量 |

### 傳回值

傳送的位元組數量。

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)