---
title: WriteDocType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เขียนการประกาศ DOCTYPE ด้วยชื่อที่ระบุและคุณลักษณะเป็นตัวเลือก
type: docs
weight: 222
url: /th/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) เมธอด

เขียนการประกาศ DOCTYPE ด้วยชื่อที่ระบุและคุณลักษณะเป็นตัวเลือก.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อของ DOCTYPE. ต้องไม่ว่าง. |
| pubid | const [String](../../../system/string/)\& | หากไม่เป็น null จะเขียน PUBLIC "pubid" "sysid" โดยที่ **pubid** และ **sysid** จะถูกแทนที่ด้วยค่าของอาร์กูเมนต์ที่ให้มา. |
| sysid | const [String](../../../system/string/)\& | หาก **pubid** เป็น null และ **sysid** ไม่เป็น null จะเขียน SYSTEM "sysid" โดยที่ **sysid** จะถูกแทนที่ด้วยค่าของอาร์กูเมนต์นี้. |
| subset | const [String](../../../system/string/)\& | หากไม่เป็น null จะเขียน [subset] โดยที่ subset จะถูกแทนที่ด้วยค่าของอาร์กูเมนต์นี้. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlTextWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)