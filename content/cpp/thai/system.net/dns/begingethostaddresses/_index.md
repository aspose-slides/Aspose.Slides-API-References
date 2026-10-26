---
title: BeginGetHostAddresses()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เริ่มการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ใหม่ของคลาส IPHostEntry โดยใช้สตริงที่ระบุซึ่งมีชื่อโฮสต์หรือที่อยู่ IP.
type: docs
weight: 131
url: /th/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ของ IPHostEntry คลาสโดยใช้สตริงที่ระบุซึ่งมีชื่อโฮสต์หรือที่อยู่ IP

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | สตริงที่มีชื่อโฮสต์หรือที่อยู่ IP |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มา ใช้เพื่อระบุแต่ละการดำเนินการแบบอะซิงโครนัสอย่างเป็นเอกลักษณ์ |

### ค่าที่ส่งกลับ

[IAsyncResult](../../../system/iasyncresult/) อ็อบเจกต์ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [Dns](../)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)