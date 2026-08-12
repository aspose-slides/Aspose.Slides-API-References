---
title: BeginGetResponse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการร้องขอแบบอะซิงโครนัสสำหรับทรัพยากร
type: docs
weight: 274
url: /th/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มต้นการร้องขอแบบอะซิงโครนัสสำหรับทรัพยากร

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุการดำเนินการแบบอะซิงโครนัสแต่ละรายการอย่างเป็นเอกลักษณ์ |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [WebRequest](../)
* เนมส페ซ [System::Net](../../)
* Library [Aspose.Slides](../../../)