---
title: Connect()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างการเชื่อมต่อกับโฮสต์ระยะไกลที่ระบุ
type: docs
weight: 248
url: /th/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) เมธอด

สร้างการเชื่อมต่อกับโฮสต์ระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | ชื่อโฮสต์ระยะไกลที่จะเชื่อมต่อ |
| port | **int32_t** | พอร์ตของโฮสต์ระยะไกลที่จะเชื่อมต่อ |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) เมธอด

สร้างการเชื่อมต่อกับโฮสต์ระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | พอร์ตของโฮสต์ระยะไกลที่จะเชื่อมต่อ |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) เมธอด

สร้างการเชื่อมต่อกับโฮสต์ระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | โฮสต์ระยะไกลที่จะเชื่อมต่อ |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) เมธอด

สร้างการเชื่อมต่อกับโฮสต์ระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | พอร์ตของโฮสต์ระยะไกลที่จะเชื่อมต่อ |

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* การกำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [TcpClient](../)
* คลาส [IPAddress](../../../system.net/ipaddress/)
* คลาส [IPEndPoint](../../../system.net/ipendpoint/)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)