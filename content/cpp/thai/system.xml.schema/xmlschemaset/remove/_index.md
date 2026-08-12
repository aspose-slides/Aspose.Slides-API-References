---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ลบสกีม่า XML Schema definition language (XSD) ที่ระบุออกจาก XmlSchemaSet.
type: docs
weight: 170
url: /th/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) เมธอด

ลบสกีม่า [Schema](../../) ของ XML definition language (XSD) ที่ระบุออกจาก [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | วัตถุ [XmlSchema](../../xmlschema/) ที่จะลบออกจาก [XmlSchemaSet](../). |

### ค่ารีเทิร์น

วัตถุ [XmlSchema](../../xmlschema/) ที่ถูกลบออกจาก [XmlSchemaSet](../) หรือ **nullptr** หากไม่พบสกีม่าใน [XmlSchemaSet](../).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchema](../../xmlschema/)
* คลาส [XmlSchemaSet](../)
* เนมสเปซ [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)