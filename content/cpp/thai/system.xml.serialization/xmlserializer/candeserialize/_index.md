---
title: CanDeserialize()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตรวจสอบว่ารีเดอร์เฉพาะอยู่ในสถานะที่สามารถทำการ deserialize ได้หรือไม่.
type: docs
weight: 1
url: /th/system.xml.serialization/xmlserializer/candeserialize/
---
## XmlSerializer::CanDeserialize(System::SharedPtr\<XmlReader\>) เมธอด

ตรวจสอบว่ารีเดอร์เฉพาะอยู่ในสถานะที่สามารถทำการ deserialize ได้หรือไม่.

```cpp
virtual bool System::Xml::Serialization::XmlSerializer::CanDeserialize(System::SharedPtr<XmlReader> xmlReader)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | รีเดอร์ที่ต้องตรวจสอบ. |

### ค่าที่ส่งกลับ

true หาก xmlReader สามารถทำการ deserialize ได้, false หากไม่เป็นเช่นนั้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* คลาส [XmlSerializer](../)
* เนมสเปซ [System::Xml::Serialization](../../)
* ไลบรารี [Aspose.Slides](../../../)