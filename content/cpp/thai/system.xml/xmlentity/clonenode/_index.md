---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างสำเนาซ้ำของโหนดนี้. โหนด Entity ไม่สามารถทำซ้ำได้. การเรียกเมธอดนี้บนวัตถุ XmlEntity จะทำให้เกิดข้อยกเว้น.
type: docs
weight: 170
url: /th/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) เมธอด


สร้างสำเนาซ้ำของโหนดนี้. โหนด Entity ไม่สามารถทำซ้ำได้. การเรียกเมธอดนี้บนวัตถุ [XmlEntity](../) จะทำให้เกิดข้อยกเว้น.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อทำสำเนาโครงย่อยของโหนดที่กำหนดอย่างเรียงลำดับ; **false** เพื่อทำสำเนาเฉพาะโหนดเท่านั้น. |

### ค่าที่ส่งคืน

สำเนาของ [XmlNode](../../xmlnode/) ที่เมธอดถูกเรียก.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlEntity](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)