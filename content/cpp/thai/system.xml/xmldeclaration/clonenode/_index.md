---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาของโหนดนี้.
type: docs
weight: 157
url: /th/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) เมธอด

สร้างสำเนาของโหนดนี้.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อคัดลอกซับทรีอย่างต่อเนื่องภายใต้โหนดที่ระบุ; **false** เพื่อคัดลอกเฉพาะโหนดเท่านั้น. เนื่องจาก [XmlDeclaration](../) โหนดไม่มีบุตร, โหนดที่คัดลอกจะรวมค่าข้อมูลเสมอ, ไม่ขึ้นกับการตั้งค่าพารามิเตอร์. |

### ค่าที่ส่งคืน

โหนดที่คัดลอก.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)