---
title: BeginGetRequestStream()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับการเขียนข้อมูลไปยังทรัพยากร.
type: docs
weight: 144
url: /th/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับการเขียนข้อมูลไปยังทรัพยากร.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้จัดให้เพื่อระบุการดำเนินการแบบอะซิงโครนัสแต่ละรายการอย่างเอกลักษณ์ |

### ค่าที่คืนกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [FileWebRequest](../)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)