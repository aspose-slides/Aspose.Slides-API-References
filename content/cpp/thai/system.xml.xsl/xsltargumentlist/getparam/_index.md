---
title: GetParam()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าพารามิเตอร์ที่สัมพันธ์กับชื่อที่กำหนดด้วยเนมสเปซ
type: docs
weight: 14
url: /th/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) method

คืนค่าพารามิเตอร์ที่สัมพันธ์กับชื่อที่กำหนดด้วยเนมสเปซ

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อของพารามิเตอร์. [XsltArgumentList](../) ไม่ได้ตรวจสอบว่าชื่อที่ส่งมานั้นเป็นชื่อท้องถิ่นที่ถูกต้องหรือไม่; อย่างไรก็ตาม ชื่อไม่สามารถเป็น **nullptr** ได้. |
| namespaceUri | const [String](../../../system/string/)\& | URI ของเนมสเปซที่สัมพันธ์กับพารามิเตอร์. |

### ค่าที่คืน

อ็อบเจ็กต์พารามิเตอร์หรือ **nullptr** หากไม่พบ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [String](../../../system/string/)
* คลาส [XsltArgumentList](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* ไลบรารี [Aspose.Slides](../../../)