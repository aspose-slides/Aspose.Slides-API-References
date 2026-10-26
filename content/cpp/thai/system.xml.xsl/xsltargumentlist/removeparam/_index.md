---
title: RemoveParam()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบพารามิเตอร์ออกจาก XsltArgumentList.
type: docs
weight: 66
url: /th/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) method


ลบพารามิเตอร์ออกจาก [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อของพารามิเตอร์ที่ต้องการลบ [XsltArgumentList](../) ไม่ได้ตรวจสอบเพื่อให้แน่ใจว่าชื่อที่ส่งเข้ามาเป็นชื่อท้องถิ่นที่ถูกต้อง; อย่างไรก็ตาม ชื่อไม่สามารถเป็น **nullptr** ได้. |
| namespaceUri | const [String](../../../system/string/)\& | URI ของเนมสเปซของพารามิเตอร์ที่ต้องการลบ. |

### ค่าที่คืนกลับ

อ็อบเจ็กต์พารามิเตอร์หรือ **nullptr** หากไม่พบ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [String](../../../system/string/)
* คลาส [XsltArgumentList](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)