---
title: DtdProcessing
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ระบุตัวเลือกสำหรับการประมวลผล DTDs. การนับประเภท DtdProcessing ถูกใช้โดยคลาส XmlReaderSettings
type: docs
weight: 638
url: /th/system.xml/dtdprocessing/
---
## DtdProcessing enum


ระบุตัวเลือกสำหรับการประมวลผล DTDs. การนับประเภท DtdProcessing ถูกใช้โดยคลาส [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### ค่า

| Name | Value | Description |
| --- | --- | --- |
| Prohibit | 0 | ระบุว่าเมื่อพบ DTD จะทำการขว้าง XmlException พร้อมข้อความที่ระบุว่าห้ามใช้ DTDs ซึ่งเป็นพฤติกรรมเริ่มต้น |
| Ignore | 1 | ทำให้ส่วนประกอบ DOCTYPE ถูกละเว้น ไม่เกิดการประมวลผล DTD และ DTD/DOCTYPE จะหายไปในการส่งออก |
| Parse | 2 | ใช้สำหรับการวิเคราะห์ DTDs |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)