---
title: IsXmlSurrogatePair()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตรวจสอบว่าคู่ตัวอักษร surrogate ที่ส่งเข้ามานั้นเป็นอักขระ XML ที่ถูกต้องหรือไม่.
type: docs
weight: 183
url: /th/system.xml/xmlconvert/isxmlsurrogatepair/
---
## XmlConvert::IsXmlSurrogatePair(char16_t, char16_t) เมธอด

ตรวจสอบว่าคู่ตัวอักษร surrogate ที่ส่งเข้ามานั้นเป็นอักขระ XML ที่ถูกต้องหรือไม่.

```cpp
static bool System::Xml::XmlConvert::IsXmlSurrogatePair(char16_t lowChar, char16_t highChar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lowChar | char16_t | ตัวอักษร surrogate ที่ต้องตรวจสอบความถูกต้อง |
| highChar | char16_t | ตัวอักษร surrogate ที่ต้องตรวจสอบความถูกต้อง |

### ค่าที่ส่งกลับ

**true** หากคู่ตัวอักษร surrogate ที่ส่งเข้ามานั้นเป็นอักขระ XML ที่ถูกต้อง; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* คลาส [XmlConvert](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)