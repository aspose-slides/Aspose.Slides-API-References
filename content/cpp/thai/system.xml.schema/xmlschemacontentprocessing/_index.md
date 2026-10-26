---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ให้ข้อมูลเกี่ยวกับโหมดการตรวจสอบความถูกต้องของการแทนที่องค์ประกอบ any และ anyAttribute.
type: docs
weight: 976
url: /th/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

ให้ข้อมูลเกี่ยวกับโหมดการตรวจสอบความถูกต้องของการแทนที่องค์ประกอบ **any** และ **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | รายการเอกสารไม่ได้รับการตรวจสอบความถูกต้อง. |
| Skip | 1 | รายการเอกสารต้องเป็น XML ที่จัดรูปแบบอย่างถูกต้องและไม่ได้รับการตรวจสอบโดยสกีม่า. |
| Lax | 2 | หากพบสกีมาที่เชื่อมโยง รายการเอกสารจะถูกตรวจสอบความถูกต้อง ไม่พบข้อผิดพลาดใด ๆ หากไม่พบ. |
| Strict | 3 | ตัวประมวลผลสกีม่า ต้องพบสกีมาที่เชื่อมโยงกับเนมสเปซที่ระบุเพื่อทำการตรวจสอบความถูกต้องของรายการเอกสาร. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)