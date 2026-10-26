---
title: XmlSchemaValidationFlags
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุตัวเลือกการตรวจสอบสกีมาที่ใช้โดยคลาส XmlSchemaValidator และ XmlReader.
type: docs
weight: 1054
url: /th/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

ระบุตัวเลือกการตรวจสอบสกีมาที่ใช้โดยคลาส [XmlSchemaValidator](../xmlschemavalidator/) และ [XmlReader](../../system.xml/xmlreader/)

```cpp
enum class XmlSchemaValidationFlags
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ไม่ประมวลผลข้อจำกัดเอกลักษณ์, สกีมาที่ฝังอยู่, คำแนะนำตำแหน่งสกีมา, หรือรายงานคำเตือนการตรวจสอบสกีม่า. |
| ProcessInlineSchema | 1 | ประมวลผลสกีมาที่ฝังอยู่ที่พบระหว่างการตรวจสอบ. |
| ProcessSchemaLocation | 2 | ประมวลผลคำแนะนำตำแหน่งสกีม่า (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) ที่พบระหว่างการตรวจสอบ. |
| ReportValidationWarnings | 4 | รายงานคำเตือนการตรวจสอบสกีม่าที่พบระหว่างการตรวจสอบ. |
| ProcessIdentityConstraints | 8 | ประมวลผลข้อจำกัดเอกลักษณ์ (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) ที่พบระหว่างการตรวจสอบ. |
| AllowXmlAttributes | 16 | อนุญาตคุณลักษณะ xml:* แม้ว่าจะไม่ได้กำหนดในสกีม่า คุณลักษณะเหล่านี้จะได้รับการตรวจสอบตามประเภทข้อมูลของมัน. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)