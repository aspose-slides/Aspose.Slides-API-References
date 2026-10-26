---
title: Connect()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างการเชื่อมต่อไปยังปลายทางระยะไกลที่ระบุ
type: docs
weight: 560
url: /th/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) เมธอด


สร้างการเชื่อมต่อไปยังปลายทางระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | ปลายทางระยะไกล |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) เมธอด


สร้างการเชื่อมต่อไปยังปลายทางระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### อาร์กิวเมนต์

| พารามิ터 | ประเภท | คำอธิบาย |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตของโฮสต์ระยะไกล |

## Socket::Connect(String, int32_t) เมธอด


สร้างการเชื่อมต่อไปยังปลายทางระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตของโฮสต์ระยะไกล |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) เมธอด


สร้างการเชื่อมต่อไปยังปลายทางระยะไกลที่ระบุ

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตของโฮสต์ระยะไกล |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [EndPoint](../../../system.net/endpoint/)
* คลาส [Socket](../)
* คลาส [IPAddress](../../../system.net/ipaddress/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)