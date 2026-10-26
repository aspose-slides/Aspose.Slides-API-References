---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างสำเนาของโหนดนี้.
type: docs
weight: 53
url: /th/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) เมธอด

สร้างสำเนาของโหนดนี้.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อทำการโคลนซับทรีอย่างต่อเนื่องภายใต้โหนดที่ระบุ; **false** เพื่อโคลนเฉพาะโหนดเองเท่านั้น. เนื่องจากโหนด CDATA ไม่มีลูกใดๆ ไม่ว่าการตั้งค่าพารามิเตอร์จะเป็นอย่างไร โหนดที่โคลนจะรวมเนื้อหาข้อมูลเสมอ. |

### ค่าที่ส่งคืน

โหนดที่ถูกโคลน.

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlCDataSection](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)