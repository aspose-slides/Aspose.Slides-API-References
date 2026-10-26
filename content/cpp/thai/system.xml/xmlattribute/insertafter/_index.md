---
title: InsertAfter()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทรกโหนดที่ระบุลงหลังจากโหนดอ้างอิงที่ระบุโดยตรง
type: docs
weight: 222
url: /th/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) เมธอด

แทรกโหนดที่ระบุลงหลังจากโหนดอ้างอิงที่ระบุโดยตรง

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) ที่จะใส่ |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) ที่เป็นโหนดอ้างอิง. **newChild** จะถูกวางหลังจาก **refChild** |

### ค่าที่ส่งกลับ

[XmlNode](../../xmlnode/) ที่ถูกแทรก

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)