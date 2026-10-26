---
title: EndGetHostByName()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่จะเสร็จสิ้น.
type: docs
weight: 66
url: /th/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่จะเสร็จสิ้น.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัส. |

### ค่าที่ส่งกลับ

อินสแตนซ์ของคลาส IPHostEntry ที่สร้างขึ้นใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPHostEntry](../../iphostentry/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Dns](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)