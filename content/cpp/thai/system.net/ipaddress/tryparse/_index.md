---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พยายามแปลงสตริงที่ส่งเข้ามาให้เป็นอินสแตนซ์ของคลาส IPAddress.
type: docs
weight: 222
url: /th/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) เมธอด

ลองแปลงสตริงที่ส่งเข้ามาให้เป็นอินสแตนซ์ของคลาส [IPAddress](../) class.

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | สตริงที่ต้องการแปลง |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | อินสแตนซ์ที่วัตถุที่แปลงแล้วจะถูกกำหนด |

### ค่าที่ส่งคืน

คืนค่า true เมื่อการแปลงสำเร็จ, มิฉะนั้นจะเป็น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [IPAddress](../)
* เนมส페ซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)