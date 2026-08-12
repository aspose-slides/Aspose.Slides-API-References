---
title: IsClientFaultCode()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'Client' หรือไม่.
type: docs
weight: 105
url: /th/system.web.services.protocols/details_soapexception/isclientfaultcode/
---
## รายละเอียด_SoapException::IsClientFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) เมธอด

ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'Client' หรือไม่.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsClientFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | รหัสข้อผิดพลาด SOAP ที่ต้องตรวจสอบ. |

### ค่าที่ส่งคืน

True เมื่อรหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'Client' มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* คลาส [Details_SoapException](../)
* เนมสเปซ [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)