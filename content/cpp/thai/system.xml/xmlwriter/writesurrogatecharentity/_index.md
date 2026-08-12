---
title: WriteSurrogateCharEntity()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เมื่อถูกเขียนทับในคลาสที่สืบทอด จะสร้างและเขียนเอนทิตีอักขระสำรองสำหรับคู่อักขระสำรอง
type: docs
weight: 261
url: /th/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) เมธอด

เมื่อถูกเขียนทับในคลาสที่สืบทอด จะสร้างและเขียนเอนทิตีอักขระสำรองสำหรับคู่อักขระสำรอง

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | ตัวอักษรส่วนล่าง. ต้องเป็นค่าระหว่าง 0xDC00 ถึง 0xDFFF. |
| highChar | char16_t | ตัวอักษรส่วนบน. ต้องเป็นค่าระหว่าง 0xD800 ถึง 0xDBFF. |

## ดูเพิ่มเติม

* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)