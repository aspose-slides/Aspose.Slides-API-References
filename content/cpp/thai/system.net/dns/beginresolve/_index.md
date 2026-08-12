---
title: BeginResolve()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เริ่มต้นการดำเนินการแบบไม่พร้อมกันเพื่อสร้างอินสแตนซ์ใหม่ของคลาส IPHostEntry-class โดยใช้ชื่อโฮสต์ที่ระบุ
type: docs
weight: 157
url: /th/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการแบบไม่พร้อมกันเพื่อสร้างอินสแตนซ์ใหม่ของคลาส IPHostEntry-class โดยใช้ชื่อโฮสต์ที่ระบุ

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | ชื่อโฮสต์ที่ใช้เพื่อสร้างอินสแตนซ์ใหม่ของคลาส [IPHostEntry](../../iphostentry/) |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้จัดหาเพื่อระบุแต่ละการดำเนินการแบบไม่พร้อมกันอย่างเป็นเอกลักษณ์ |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบไม่พร้อมกันที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [Dns](../)
* เนมส페ซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)