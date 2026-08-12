---
title: CloneNode()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสำเนาของโหนดนี้.
type: docs
weight: 92
url: /th/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) เมธอด


สร้างสำเนาของโหนดนี้.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อทำการโคลนซับทรีอย่างต่อเนื่องใต้โหนดที่ระบุ; **false** เพื่อโคลนเฉพาะโหนดเอง. สำหรับโหนด [XmlEntityReference](../) เมธอดนี้จะคืนค่าโหนดอ้างอิงเอนทิตีที่ไม่มีลูก. ข้อความแทนที่จะถูกตั้งค่าเมื่อโหนดถูกแทรกเข้าไปในพาเรนท์. |

### ค่าที่ส่งคืน

โหนดที่ถูกโคลน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)