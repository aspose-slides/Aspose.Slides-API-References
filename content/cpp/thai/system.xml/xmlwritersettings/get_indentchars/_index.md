---
title: get_IndentChars()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ส่งคืนสตริงอักขระที่จะใช้เมื่อทำการเยื้อง การตั้งค่านี้ใช้เมื่อค่าของ XmlWriterSettings::set_Indent ถูกตั้งเป็น true."
type: docs
weight: 131
url: /th/system.xml/xmlwritersettings/get_indentchars/
---
## XmlWriterSettings::get_IndentChars() เมธอด

ส่งคืนสตริงอักขระที่จะใช้เมื่อทำการเยื้อง. การตั้งค่านี้ใช้เมื่อค่าของ [XmlWriterSettings::set_Indent](../set_indent/) ถูกตั้งเป็น **true**.

```cpp
String System::Xml::XmlWriterSettings::get_IndentChars()
```

### ค่าที่ส่งคืน

สตริงอักขระที่จะใช้เมื่อทำการเยื้อง. ค่านี้สามารถตั้งเป็นค่าสตริงใดก็ได้. อย่างไรก็ตาม เพื่อให้แน่ใจว่า XML ถูกต้อง คุณควรระบุอักขระช่องว่างที่เป็นค่าที่ถูกต้องเท่านั้น เช่น อักขระช่องว่าง, แท็บ, แครินจ์รีเทิร์น หรือไลน์ฟีด. ค่าเริ่มต้นคือสองช่องว่าง.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlWriterSettings](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)