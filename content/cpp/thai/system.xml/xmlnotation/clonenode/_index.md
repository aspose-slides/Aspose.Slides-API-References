---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: สร้างสำเนาซ้ำของโหนดนี้ โหนด Notation ไม่สามารถทำสำเนาได้ การเรียกใช้เมธอดนี้บนอ็อบเจ็กต์ XmlNotation จะทำให้เกิดข้อยกเว้น.
type: docs
weight: 118
url: /th/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) เมธอด

สร้างสำเนาซ้ำของโหนดนี้ โหนด Notation ไม่สามารถทำสำเนาได้ การเรียกใช้เมธอดนี้บนอ็อบเจ็กต์ [XmlNotation](../) จะทำให้เกิดข้อยกเว้น.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อทำการโคลนต้นไม้ย่อยภายใต้โหนดที่ระบุแบบเรียกซ้ำ; **false** เพื่อโคลนเฉพาะโหนดเท่านั้น. |

### ค่าที่ส่งคืน

สำเนา [XmlNode](../../xmlnode/) ของโหนดที่เมธอดถูกเรียกใช้.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlNotation](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)