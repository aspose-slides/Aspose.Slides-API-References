---
title: Add()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มสคีมาที่ตั้งอยู่ตาม URL ที่กำหนดลงในคอลเลกชันสคีมา.
type: docs
weight: 40
url: /th/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) เมธอด

เพิ่มสคีมาที่อยู่ตาม URL ที่กำหนดลงในคอลเลกชันสคีมา

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่เชื่อมโยงกับสคีมา สำหรับ XML Schemas โดยทั่วไปจะเป็น **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | URL ที่ระบุสคีมาที่ต้องการโหลด. |

### ค่าที่ส่งกลับ

[XmlSchema](../../xmlschema/) ที่ถูกเพิ่มลงในคอลเลกชันสคีมา; **nullptr** หากสคีมาที่เพิ่มเป็น XDR schema หรือมีข้อผิดพลาดในการคอมไพล์สคีมา.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) เมธอด

เพิ่มสคีมาที่อยู่ใน [XmlReader](../../../system.xml/xmlreader/) ลงในคอลเลกชันสคีมา

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่เชื่อมโยงกับสคีมา สำหรับ XML Schemas โดยทั่วไปจะเป็น **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่มีสคีมาที่จะเพิ่ม. |

### ค่าที่ส่งกลับ

[XmlSchema](../../xmlschema/) ที่ถูกเพิ่มลงในคอลเลกชันสคีมา; **nullptr** หากสคีมาที่เพิ่มเป็น XDR schema หรือมีข้อผิดพลาดในการคอมไพล์สคีมา.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) เมธอด

เพิ่มสคีมาที่อยู่ใน [XmlReader](../../../system.xml/xmlreader/) ลงในคอลเลกชันสคีมา. [XmlResolver](../../../system.xml/xmlresolver/) ที่ระบุจะใช้เพื่อแก้ไขทรัพยากรภายนอกใด ๆ.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่เชื่อมโยงกับสคีมา สำหรับ XML Schemas โดยทั่วไปจะเป็น **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่มีสคีมาที่จะเพิ่ม. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขเนมสเปซที่อ้างอิงในองค์ประกอบ **include** และ **import** หรือแอตทริบิวต์ **x-schema** (สคีมา XDR). หากเป็น **nullptr** การอ้างอิงภายนอกจะไม่ถูกแก้ไข. |

### ค่าที่ส่งกลับ

[XmlSchema](../../xmlschema/) ที่ถูกเพิ่มลงในคอลเลกชันสคีมา; **nullptr** หากสคีมาที่เพิ่มเป็น XDR schema หรือมีข้อผิดพลาดในการคอมไพล์สคีมา.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) เมธอด

เพิ่ม [XmlSchema](../../xmlschema/) ลงในคอลเลกชัน

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) ที่จะเพิ่มลงในคอลเลกชัน. |

### ค่าที่ส่งกลับ

[XmlSchema](../../xmlschema/) อ็อบเจกต์.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) เมธอด

เพิ่ม [XmlSchema](../../xmlschema/) ลงในคอลเลกชัน. [XmlResolver](../../../system.xml/xmlresolver/) ที่ระบุจะใช้เพื่อแก้ไขการอ้างอิงภายนอกใด ๆ.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) ที่จะเพิ่มลงในคอลเลกชัน. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขเนมสเปซที่อ้างอิงในองค์ประกอบ **include** และ **import**. หากเป็น **nullptr** การอ้างอิงภายนอกจะไม่ถูกแก้ไข. |

### ค่าที่ส่งกลับ

[XmlSchema](../../xmlschema/) ที่ถูกเพิ่มลงในคอลเลกชันสคีมา.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) เมธอด

เพิ่มเนมสเปซทั้งหมดที่กำหนดในคอลเลกชันที่ให้ (รวมถึงสคีมาที่เชื่อมโยง) ลงในคอลเลกชันนี้

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) ที่คุณต้องการเพิ่มลงในคอลเลกชันนี้. |

## ดูเพิ่ม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchema](../../xmlschema/)
* คลาส [String](../../../system/string/)
* คลาส [XmlSchemaCollection](../)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* คลาส [XmlResolver](../../../system.xml/xmlresolver/)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)