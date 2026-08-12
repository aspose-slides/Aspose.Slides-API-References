---
title: BeginGetRequestStream()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร.
type: docs
weight: 469
url: /th/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method

เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่ถูกเรียกเมื่อการดำเนินการเสร็จสมบูรณ์ |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้จัดเตรียมใช้เพื่อระบุแต่ละการดำเนินการแบบอะซิงโครนัสอย่างเป็นเอกลักษณ์ |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่ถูกเริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [HttpWebRequest](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)