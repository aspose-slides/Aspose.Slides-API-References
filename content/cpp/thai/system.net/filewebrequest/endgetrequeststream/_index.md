---
title: EndGetRequestStream()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รอจนกว่าการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อรับสตรีมจะเสร็จสิ้น
type: docs
weight: 157
url: /th/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการทำงานแบบอะซิงโครนัสที่ระบุเพื่อรับสตรีมจะเสร็จสิ้น

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีม |

### ค่าที่คืนกลับ

สตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [FileWebRequest](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)