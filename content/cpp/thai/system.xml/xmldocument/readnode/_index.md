---
title: ReadNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอ็อบเจกต์ XmlNode ตามข้อมูลใน XmlReader ตัวอ่านต้องถูกจัดตำแหน่งที่โหนดหรือแอตทริบิวต์
type: docs
weight: 495
url: /th/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) เมธอด

สร้างอ็อบเจกต์ [XmlNode](../../xmlnode/) ตามข้อมูลใน [XmlReader](../../xmlreader/). ตัวอ่านต้องถูกจัดตำแหน่งที่โหนดหรือแอตทริบิวต์.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | แหล่งข้อมูล XML. |

### ค่าที่ส่งกลับ

อ็อบเจกต์ใหม่ [XmlNode](../../xmlnode/) หรือ **nullptr** หากไม่มีโหนดเหลืออยู่.

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlReader](../../xmlreader/)
* คลาส [XmlDocument](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)