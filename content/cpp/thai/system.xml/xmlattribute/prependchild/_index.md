---
title: PrependChild()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มโหนดที่ระบุไปยังจุดเริ่มต้นของรายการโหนดลูกสำหรับโหนดนี้
type: docs
weight: 261
url: /th/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) เมธอด


เพิ่มโหนดที่ระบุไปยังจุดเริ่มต้นของรายการโหนดลูกสำหรับโหนดนี้.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) ที่จะเพิ่ม หากเป็น [XmlDocumentFragment](../../xmldocumentfragment/) เนื้อหาทั้งหมดของส่วนเอกสารจะถูกย้ายไปยังรายการโหนดลูกของโหนดนี้ |

### ค่ารีเทิร์น

[XmlNode](../../xmlnode/) ที่เพิ่ม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlAttribute](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)