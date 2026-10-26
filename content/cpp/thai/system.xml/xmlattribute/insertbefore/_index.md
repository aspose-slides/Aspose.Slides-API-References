---
title: InsertBefore()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกโหนดที่ระบุโดยตรงก่อนโหนดอ้างอิงที่ระบุ
type: docs
weight: 209
url: /th/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) เมธอด

แทรกโหนดที่ระบุโดยตรงก่อนโหนดอ้างอิงที่ระบุ

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) ที่จะทำการแทรก |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) ที่เป็นโหนดอ้างอิง. **newChild** จะถูกวางก่อนโหนดนี้ |

### ค่าที่ส่งคืน

[XmlNode](../../xmlnode/) ที่แทรก

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlAttribute](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)