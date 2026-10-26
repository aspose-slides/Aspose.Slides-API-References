---
title: Reprocess()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประมวลผลซ้ำสกีมภาษา XML Schema definition language (XSD) ที่มีอยู่แล้วใน XmlSchemaSet.
type: docs
weight: 222
url: /th/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) เมธอด

ประมวลผลซ้ำสกีมภาษา XML [Schema](../../) (XSD) ที่มีอยู่แล้วใน [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | สกีมที่จะประมวลผลซ้ำ |

### ค่าที่คืนกลับ

วัตถุ [XmlSchema](../../xmlschema/) หากสกีมเป็นสกีมที่ถูกต้อง หากสกีมไม่ถูกต้องและมีการระบุ ValidationEventHandler จะคืนค่า **nullptr** และเกิดเหตุการณ์การตรวจสอบที่เหมาะสม มิฉะนั้นจะเกิดข้อยกเว้น XmlSchemaException.

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchema](../../xmlschema/)
* คลาส [XmlSchemaSet](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)