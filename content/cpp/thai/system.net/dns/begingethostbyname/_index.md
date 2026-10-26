---
title: BeginGetHostByName()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่โดยใช้ชื่อโฮสต์ที่ระบุ.
type: docs
weight: 53
url: /th/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry ใหม่โดยใช้ชื่อโฮสต์ที่ระบุ

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | ชื่อโฮสต์ |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คำเรียกกลับที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ระบุใช้เพื่อระบุแต่ละการดำเนินการแบบอะซิงโครนัสอย่างเป็นเอกลักษณ์ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [Dns](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)