---
title: CreateDocumentType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนวัตถุ XmlDocumentType ใหม่.
type: docs
weight: 313
url: /th/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method

ส่งคืนวัตถุ [XmlDocumentType](../../xmldocumenttype/) ใหม่

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อของประเภทเอกสาร |
| publicId | const [String](../../../system/string/)\& | ตัวระบุสาธารณะของประเภทเอกสารหรือ **nullptr** คุณสามารถระบุ URI สาธารณะและตัวระบุระบบเพื่อระบุตำแหน่งของส่วนย่อย DTD ภายนอก |
| systemId | const [String](../../../system/string/)\& | ตัวระบุระบบของประเภทเอกสารหรือ **nullptr** ระบุ URL ของตำแหน่งไฟล์สำหรับส่วนย่อย DTD ภายนอก |
| internalSubset | const [String](../../../system/string/)\& | ส่วนย่อยภายใน DTD ของประเภทเอกสารหรือ **nullptr** |

### ค่าที่คืนกลับ

วัตถุ [XmlDocumentType](../../xmldocumenttype/) ใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlDocumentType](../../xmldocumenttype/)
* คลาส [String](../../../system/string/)
* คลาส [XmlDocument](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)