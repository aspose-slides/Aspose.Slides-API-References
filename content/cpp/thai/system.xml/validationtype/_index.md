---
title: ValidationType
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุประเภทของการตรวจสอบที่ต้องทำ.
type: docs
weight: 729
url: /th/system.xml/validationtype/
---
## ValidationType enum

ระบุประเภทของการตรวจสอบที่ต้องทำ

```cpp
enum class ValidationType
```

### ค่า

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | ไม่มีการตรวจสอบใด ๆ ถูกทำ และไม่มีข้อผิดพลาดจากการตรวจสอบถูกโยนออก การตั้งค่านี้สร้างตัวแยกวิเคราะห์แบบไม่ตรวจสอบที่สอดคล้องกับ XML 1.0 |
| Auto | 1 | ทำการตรวจสอบหากพบข้อมูล DTD หรือสคีม่า |
| DTD | 2 | ทำการตรวจสอบตาม DTD |
| XDR | 3 | ตรวจสอบตามสคีม่า XML-Data Reduced (XDR) รวมถึงสคีม่า XDR แบบอินไลน์ สคีม่า XDR จะถูกรู้จำโดยใช้คำนำหน้าของเนมสเปซ **x-schema** หรือค่า [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) |
| Schema | 4 | ตรวจสอบตามสคีม่า XML [Schema](../../system.xml.schema/) definition language (XSD) รวมถึงสคีม่า XML แบบอินไลน์ สคีม่า XML จะเชื่อมโยงกับ URI ของเนมสเปซโดยใช้แอตทริบิวต์ **schemaLocation** หรือ **Schemas** ที่ให้มา |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)