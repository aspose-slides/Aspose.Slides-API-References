---
title: get_SchemaInfo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนข้อมูลสกีมาที่ได้รับการกำหนดให้โหนดปัจจุบันเป็นผลมาจากการตรวจสอบสกีมา.
type: docs
weight: 196
url: /th/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() เมธอด

ส่งคืนข้อมูลสกีมาที่ได้รับการกำหนดให้โหนดปัจจุบันเป็นผลมาจากการตรวจสอบสกีมา.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### ค่าที่ส่งคืน

อ็อบเจ็กต์ IXmlSchemaInfo ที่ประกอบด้วยข้อมูลสกีมาสำหรับโหนดปัจจุบัน. [Schema](../../../system.xml.schema/) ข้อมูลสามารถตั้งค่าได้บนองค์ประกอบ, แอตทริบิวต์, หรือบนโหนดข้อความที่มีค่า [XmlReader::get_ValueType](../get_valuetype/) ไม่เป็น null. หากโหนดปัจจุบันไม่ใช่หนึ่งในประเภทโหนดข้างต้น, หรือหากอินสแตนซ์ [XmlReader](../) ไม่รายงานข้อมูลสกีมา, เมธอดนี้จะส่งคืน **nullptr**. หากเมธอดนี้ถูกเรียกจากออบเจ็กต์ [XmlTextReader](../../xmltextreader/) หรือออบเจ็กต์ [XmlValidatingReader](../../xmlvalidatingreader/), เมธอดนี้จะส่งคืน **nullptr** เสมอ. การทำงาน [XmlReader](../) เหล่านี้ไม่เปิดเผยข้อมูลสกีมาผ่านเมธอด get_SchemaInfo.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)