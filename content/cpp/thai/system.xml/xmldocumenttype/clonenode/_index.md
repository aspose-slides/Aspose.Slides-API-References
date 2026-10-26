---
title: CloneNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาซ้ำของโหนดนี้.
type: docs
weight: 118
url: /th/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) เมธอด


สร้างสำเนาซ้ำของโหนดนี้.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| deep | **bool** | **true** เพื่อทำการคัดลอกต้นไม้ย่อยของโหนดที่ระบุอย่างต่อเนื่อง; **false** เพื่อคัดลอกเฉพาะโหนดเอง. สำหรับโหนดประเภทเอกสาร, โหนดที่คัดลอกจะรวมต้นไม้ย่อยเสมอ, โดยไม่คำนึงถึงการตั้งค่าพารามิเตอร์. |

### ค่าที่ส่งคืน

โหนดที่คัดลอก

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlDocumentType](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)