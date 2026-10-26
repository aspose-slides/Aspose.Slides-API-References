---
title: get_NameTable()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: คืนค่า XmlNameTable ที่ใช้สำหรับการเปรียบเทียบสตริงที่เป็นอะตอม
type: docs
weight: 1
url: /th/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() เมธอด


คืนค่า [XmlNameTable](../../xmlnametable/) ที่ใช้สำหรับการเปรียบเทียบสตริงที่เป็นอะตอม

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### ค่าที่ส่งคืน

[XmlNameTable](../../xmlnametable/) ที่เก็บสตริงที่เป็นอะตอมทั้งหมดที่ใช้โดยทุก [XmlReader](../../xmlreader/) อินสแตนซ์ที่สร้างโดยใช้วัตถุ [XmlReaderSettings](../) นี้ ค่าดีฟอลต์คือ **nullptr** อินสแตนซ์ [XmlReader](../../xmlreader/) ที่สร้างขึ้นจะใช้ [NameTable](../../nametable/) ว่างใหม่หากค่านี้เป็น **nullptr**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNameTable](../../xmlnametable/)
* คลาส [XmlReaderSettings](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)