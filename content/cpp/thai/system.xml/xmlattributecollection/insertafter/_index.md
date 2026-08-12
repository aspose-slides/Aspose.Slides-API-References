---
title: InsertAfter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกแอตทริบิวต์ที่ระบุไว้ทันทีหลังจากแอตทริบิวต์อ้างอิงที่ระบุ
type: docs
weight: 66
url: /th/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) เมธอด

แทรกแอตทริบิวต์ที่ระบุไว้ทันทีหลังจากแอตทริบิวต์อ้างอิงที่ระบุ

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | แอตทริบิวต์ที่จะถูกแทรก |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | แอตทริบิวต์อ้างอิง. **newNode** จะถูกวางหลังจาก **refNode**. |

### ค่าที่คืนกลับ

[XmlAttribute](../../xmlattribute/) ที่จะถูกแทรกเข้าไปในคอลเลกชัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)