---
title: Receive()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืน datagram ที่ส่งโดยเซิร์ฟเวอร์.
type: docs
weight: 92
url: /th/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) เมธอด

ส่งคืน datagram ที่ส่งโดยเซิร์ฟเวอร์.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | อ็อบเจ็กต์ [IPEndPoint](../../../system.net/ipendpoint/) ที่แสดงถึงโฮสต์ระยะไกลที่ข้อมูลถูกส่ง |

### ค่าที่ส่งกลับ

อาร์เรย์ไบต์ที่ข้อมูลที่ได้รับจะถูกกำหนดให้

## ดูเพิ่มเติม

* การกำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IPEndPoint](../../../system.net/ipendpoint/)
* คลาส [UdpClient](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)