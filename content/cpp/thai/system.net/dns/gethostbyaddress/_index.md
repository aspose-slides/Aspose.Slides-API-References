---
title: GetHostByAddress()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่โดยใช้การแทนค่าเป็นสตริงของที่อยู่ IP ที่ระบุ
type: docs
weight: 14
url: /th/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) เมธอด

สร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่โดยใช้การแทนค่าเป็นสตริงของที่อยู่ IP ที่ระบุ

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| address | [String](../../../system/string/) | การแทนค่าเป็นสตริงของที่อยู่ IP |

### ค่าที่ส่งคืน

อินสแตนซ์ของคลาส IPHostEntry ที่สร้างใหม่

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) เมธอด

สร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่โดยใช้ที่อยู่ IP ที่ระบุ

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | ที่อยู่ IP |

### ค่าที่ส่งคืน

อินสแตนซ์ของคลาส IPHostEntry ที่สร้างใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPHostEntry](../../iphostentry/)
* คลาส [String](../../../system/string/)
* คลาส [Dns](../)
* คลาส [IPAddress](../../ipaddress/)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)