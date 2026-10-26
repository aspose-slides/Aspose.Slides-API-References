---
title: IsMustUnderstandFaultCode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'MustUnderstand' หรือไม่.
type: docs
weight: 118
url: /th/system.web.services.protocols/details_soapexception/ismustunderstandfaultcode/
---
## Details_SoapException::IsMustUnderstandFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) เมธอด

ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'MustUnderstand' หรือไม่.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsMustUnderstandFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | รหัสข้อผิดพลาด SOAP ที่จะตรวจสอบ. |

### ค่าที่คืน

คืนค่า true เมื่อรหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'MustUnderstand' มิฉะนั้นจะคืนค่า false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* คลาส [Details_SoapException](../)
* เนมสเปซ [System::Web::Services::Protocols](../../)
* ไลบรารี [Aspose.Slides](../../../)