---
title: BeginGetRequestStream()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร
type: docs
weight: 300
url: /th/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุแต่ละการดำเนินการแบบอะซิงโครนัสอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) แสดงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [WebRequest](../)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)