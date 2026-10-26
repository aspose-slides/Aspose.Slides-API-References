---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างและเขียนเอนทิตีอักขระแทนที่สำหรับคู่อักขระ surrogate
type: docs
weight: 391
url: /th/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) เมธอด

สร้างและเขียนเอนทิตีอักขระแทนที่สำหรับคู่อักขระ surrogate

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | ตัวอักษร surrogate ต่ำ ค่านี้ต้องอยู่ระหว่าง **0xDC00** ถึง **0xDFFF** |
| highChar | char16_t | ตัวอักษร surrogate สูง ค่านี้ต้องอยู่ระหว่าง **0xD800** ถึง **0xDBFF** |

## See Also

* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)