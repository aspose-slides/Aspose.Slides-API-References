---
title: WriteDocType()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เมื่อถูกเขียนทับในคลาสที่สืบทอด จะเขียนการประกาศ DOCTYPE ด้วยชื่อที่ระบุและแอตทริบิวต์ที่เป็นตัวเลือก
type: docs
weight: 79
url: /th/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) เมธอด

เมื่อถูกเขียนทับในคลาสที่สืบทอด จะเขียนการประกาศ DOCTYPE ด้วยชื่อที่ระบุและแอตทริบิวต์ที่เป็นตัวเลือก

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อของ DOCTYPE นี้ต้องไม่เป็นค่าว่าง |
| pubid | const [String](../../../system/string/)\& | หากไม่เป็นค่า null จะเขียน PUBLIC \"pubid\" \"sysid\" โดยที่ **pubid** และ **sysid** จะถูกแทนที่ด้วยค่าของอาร์กิวเมนต์ที่ให้มา |
| sysid | const [String](../../../system/string/)\& | หาก **pubid** เป็น **nullptr** และ **sysid** ไม่เป็น null จะเขียน SYSTEM \"sysid\" โดยที่ **sysid** จะถูกแทนที่ด้วยค่าของอาร์กิวเมนต์นี้ |
| subset | const [String](../../../system/string/)\& | หากไม่เป็น null จะเขียน [subset] โดยที่ subset จะถูกแทนที่ด้วยค่าของอาร์กิวเมนต์นี้ |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)