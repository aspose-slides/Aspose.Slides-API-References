---
title: InferSchema()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สรุปสคีม่า XML Schema Definition Language (XSD) จากเอกสาร XML ที่บรรจุอยู่ในอ็อบเจ็กต์ XmlReader ที่ระบุ
type: docs
weight: 66
url: /th/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) เมธอด

สรุปสคีม่า XML [Schema](../../) Definition Language (XSD) จากเอกสาร XML ที่บรรจุอยู่ในอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ระบุ

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสาร XML เพื่อสรุปสคีม่า |

### ค่าที่คืนกลับ

อ็อบเจ็กต์ [XmlSchemaSet](../../xmlschemaset/) ที่บรรจุสคีม่าที่สรุปได้

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) เมธอด

สรุปสคีม่า XML [Schema](../../) Definition Language (XSD) จากเอกสาร XML ที่บรรจุอยู่ในอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่ระบุและปรับปรุงสคีม่าโดยใช้สคีม่าเดิมในอ็อบเจ็กต์ [XmlSchemaSet](../../xmlschemaset/) ที่ระบุที่มีเนมสเปซเป้าหมายเดียวกัน

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสาร XML เพื่อสรุปสคีม่า |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | อ็อบเจ็กต์ [XmlSchemaSet](../../xmlschemaset/) ที่บรรจุสคีม่าเดิมที่ใช้ในการปรับปรุงสคีม่าที่สรุป |

### ค่าที่คืนกลับ

อ็อบเจ็กต์ [XmlSchemaSet](../../xmlschemaset/) ที่บรรจุสคีม่าโดยสรุป

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)