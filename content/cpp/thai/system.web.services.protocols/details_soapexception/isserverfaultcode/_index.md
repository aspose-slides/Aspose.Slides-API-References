---
title: IsServerFaultCode()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตรวจสอบว่าโค้ดที่ระบุเท่ากับโค้ดข้อผิดพลาด SOAP ประเภท 'Server' หรือไม่.
type: docs
weight: 131
url: /th/system.web.services.protocols/details_soapexception/isserverfaultcode/
---
## Details_SoapException::IsServerFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) เมธอด

ตรวจสอบว่าโค้ดที่ระบุเท่ากับโค้ดข้อผิดพลาด SOAP ประเภท 'Server' หรือไม่.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsServerFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | โค้ดข้อผิดพลาด SOAP ที่ต้องการตรวจสอบ |

### ค่าที่ส่งกลับ

True เมื่อโค้ดที่ระบุเท่ากับโค้ดข้อผิดพลาด SOAP ประเภท 'Server' มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* คลาส [Details_SoapException](../)
* เนมสเปซ [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)