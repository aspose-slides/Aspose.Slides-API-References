---
title: BeginGetResponse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการร้องขอแบบอะซิงโครนัสสำหรับทรัพยากร.
type: docs
weight: 495
url: /th/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการร้องขอแบบอะซิงโครนัสสำหรับทรัพยากร.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้ในการระบุแต่ละการดำเนินการแบบอะซิงโครนัสอย่างไม่ซ้ำกัน. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [HttpWebRequest](../)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)