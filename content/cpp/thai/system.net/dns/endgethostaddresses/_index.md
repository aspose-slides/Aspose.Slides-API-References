---
title: EndGetHostAddresses()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อสร้างอินสแตนซ์ของ IPHostEntry-class จะเสร็จสมบูรณ์.
type: docs
weight: 144
url: /th/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) method

รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อสร้างอินสแตนซ์ของ IPHostEntry-class จะเสร็จสิ้น.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัส. |

### ค่าที่ส่งกลับ

อินสแตนซ์ของ IPHostEntry-class ที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)