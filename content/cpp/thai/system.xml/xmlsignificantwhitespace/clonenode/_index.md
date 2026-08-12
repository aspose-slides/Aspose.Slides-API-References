---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างสำเนาของโหนดนี้
type: docs
weight: 79
url: /th/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) เมธอด


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อโคลนส่วนย่อยของต้นไม้ย่อยอย่างต่อเนื่องภายใต้โหนดที่ระบุ; **false** เพื่อโคลนเฉพาะโหนดเองเท่านั้น. สำหรับโหนดที่เป็นช่องว่างสำคัญ, โหนดที่โคลนจะรวมค่าข้อมูลเสมอ, ไม่ว่าจะตั้งค่าพารามิเตอร์อย่างไรก็ตาม. |

### ค่าที่ส่งคืน

โหนดที่โคลน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlSignificantWhitespace](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)