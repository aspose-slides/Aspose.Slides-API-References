---
title: NewLineHandling
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดวิธีการจัดการการขึ้นบรรทัดใหม่.
type: docs
weight: 690
url: /th/system.xml/newlinehandling/
---
## NewLineHandling enum


กำหนดวิธีการจัดการการขึ้นบรรทัดใหม่.

```cpp
enum class NewLineHandling
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Replace | 0 | อักขระการขึ้นบรรทัดใหม่จะถูกแทนที่เพื่อให้ตรงกับอักขระที่ระบุในค่า [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | อักขระการขึ้นบรรทัดใหม่จะถูกแปลงเป็นเอนทิตี้ การตั้งค่านี้จะคงอักขระทั้งหมดไว้เมื่อผลลัพธ์ถูกอ่านโดย [XmlReader](../xmlreader/) ที่ทำการทำให้เป็นมาตรฐาน. |
| None | 2 | อักขระการขึ้นบรรทัดใหม่จะไม่เปลี่ยนแปลง ผลลัพธ์จะเหมือนกับอินพุต. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)