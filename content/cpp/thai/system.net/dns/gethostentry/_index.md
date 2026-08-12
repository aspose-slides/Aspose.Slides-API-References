---
title: GetHostEntry()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ IPHostEntry-class ใหม่โดยใช้สตริงที่ระบุซึ่งมีชื่อโฮสต์หรือที่อยู่ IP.
type: docs
weight: 79
url: /th/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) เมธอด

Creates a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | สตริงที่มีชื่อโฮสต์หรือที่อยู่ IP. |

### ค่าที่ส่งกลับ

อินสแตนซ์ IPHostEntry-class ที่สร้างใหม่.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) เมธอด

Creates a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | ที่อยู่ IP. |

### ค่าที่ส่งกลับ

อินสแตนซ์ IPHostEntry-class ที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPHostEntry](../../iphostentry/)
* คลาส [String](../../../system/string/)
* คลาส [Dns](../)
* คลาส [IPAddress](../../ipaddress/)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)