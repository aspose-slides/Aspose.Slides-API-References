---
title: EndGetRequestStream()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อรับสตรีมจะเสร็จสมบูรณ์
type: docs
weight: 313
url: /th/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมจะเสร็จสมบูรณ์.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่เป็นตัวแทนของการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีม |

### ค่าที่ส่งกลับ

สตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [WebRequest](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)