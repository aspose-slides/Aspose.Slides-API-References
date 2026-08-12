---
title: EndGetRequestStream()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อรับสตรีมจะเสร็จสิ้น
type: docs
weight: 482
url: /th/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อรับสตรีมจะเสร็จสิ้น.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีม. |

### ค่าที่ส่งคืน

สตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [HttpWebRequest](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)