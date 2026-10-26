---
title: Connect()
second_title: Aspose.Slides C++ API 參考
description: 在指定的主機上與指定的埠建立連線。
type: docs
weight: 66
url: /zh-hant/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) 方法

建立與指定主機上指定埠的連線。

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 您欲連接之遠端 DNS 主機名稱。 |
| port | **int32_t** | 您欲通訊之本機埠號。 |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) 方法

建立與指定位址上指定埠之主機的連線。

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 用於傳送資料的遠端主機[IPAddress](../../../system.net/ipaddress/)。 |
| port | **int32_t** | 您欲通訊之本機埠號。 |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) 方法

建立與遠端端點的連線。

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 您綁定 UDP 連線的端點。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)