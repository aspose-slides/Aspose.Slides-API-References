---
title: InsertBefore()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกแอตทริบิวต์ที่ระบุทันทีก่อนแอตทริบิวต์อ้างอิงที่ระบุ.
type: docs
weight: 53
url: /th/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) เมธอด

แทรกแอตทริบิวต์ที่ระบุทันทีก่อนแอตทริบิวต์อ้างอิงที่ระบุ.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | แอตทริบิวต์ที่จะถูกแทรก. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | แอตทริบิวต์อ้างอิง. **newNode** ถูกวางไว้ก่อน **refNode**. |

### ค่าที่คืน

[XmlAttribute](../../xmlattribute/) ที่จะถูกแทรกเข้าไปในคอลเลกชัน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlAttribute](../../xmlattribute/)
* คลาส [XmlAttributeCollection](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)