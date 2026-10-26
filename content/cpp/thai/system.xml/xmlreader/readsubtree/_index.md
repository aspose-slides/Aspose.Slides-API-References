---
title: ReadSubtree()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนอินสแตนซ์ XmlReader ใหม่ที่สามารถใช้เพื่ออ่านโหนดปัจจุบันและโหนดลูกทั้งหมดของมัน.
type: docs
weight: 963
url: /th/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() เมธอด


คืนค่าออบเจกต์ [XmlReader](../) ใหม่ที่สามารถใช้เพื่ออ่านโหนดปัจจุบันและโหนดลูกทั้งหมดของมัน.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### ค่าที่คืน

ออบเจกต์ XML reader ใหม่ที่ตั้งค่าเป็น [ReadState::Initial](../../readstate/). การเรียกใช้เมธอด [XmlReader::Read](../read/) จะวางตำแหน่งรีดเดอร์ใหม่บนโหนดที่เป็นโหนดปัจจุบันก่อนการเรียกเมธอด [XmlReader::ReadSubtree](./).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)