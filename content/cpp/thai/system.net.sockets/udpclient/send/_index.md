---
title: Send()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่ง datagram UDP ไปยังโฮสต์ที่จุดสิ้นสุดระยะไกล.
type: docs
weight: 79
url: /th/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) เมธอด

ส่ง datagram UDP ไปยังโฮสต์ที่จุดสิ้นสุดระยะไกล.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ของประเภท [Byte](../../../system/byte/) เพื่อส่ง |
| bytes | **int32_t** | จำนวนไบต์ใน datagram |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | [IPEndPoint](../../../system.net/ipendpoint/) ที่แสดงโฮสต์และพอร์ตที่ต้องการส่ง datagram |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ส่ง

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) เมธอด

ส่ง datagram UDP ไปยังพอร์ตที่ระบุบนโฮสต์ระยะไกลที่ระบุ.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ของประเภท [Byte](../../../system/byte/) เพื่อส่ง |
| bytes | **int32_t** | จำนวนไบต์ใน datagram |
| hostname | [String](../../../system/string/) | ชื่อของโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ส่ง

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) เมธอด

ส่ง datagram UDP ไปยังโฮสต์ระยะไกล.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ของประเภท [Byte](../../../system/byte/) เพื่อส่ง |
| bytes | **int32_t** | จำนวนไบต์ใน datagram |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ส่ง

## ดูเพิ่มเติม

* กำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IPEndPoint](../../../system.net/ipendpoint/)
* คลาส [UdpClient](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)