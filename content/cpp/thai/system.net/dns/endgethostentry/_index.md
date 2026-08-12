---
title: EndGetHostEntry()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่จะเสร็จสมบูรณ์.
type: docs
weight: 118
url: /th/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่จะเสร็จสมบูรณ์.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | วัตถุ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัส |

### ค่าที่ส่งคืน

อินสแตนซ์ของคลาส IPHostEntry ที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPHostEntry](../../iphostentry/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Dns](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)