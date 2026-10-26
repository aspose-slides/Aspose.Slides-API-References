---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาที่ซ้ำของโหนดนี้.
type: docs
weight: 40
url: /th/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) เมธอด


สร้างสำเนาที่ซ้ำของโหนดนี้.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อทำการโคลนซับต้นไม้โดยเรียกซ้ำภายใต้โหนดที่ระบุ; **false** เพื่อโคลนเฉพาะโหนดเอง. เนื่องจากโหนดคอมเมนต์ไม่มีลูก, โหนดที่โคลนจะรวมข้อความเสมอไม่ว่าจะตั้งค่าพารามิเตอร์อย่างไร. |

### ค่าที่ส่งคืน

โหนดที่คัดลอก.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlComment](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)