---
title: SetNamedItem()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "เพิ่ม XmlNode โดยใช้ค่าของ XmlNode::get_Name"
type: docs
weight: 27
url: /th/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) เมธอด

เพิ่ม [XmlNode](../../xmlnode/) โดยใช้ค่า [XmlNode::get_Name](../../xmlnode/get_name/) ของมัน.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) ที่จะจัดเก็บใน [XmlNamedNodeMap](../). หากมีโหนดที่มีชื่อนั้นอยู่แล้วในแผนที่ จะถูกแทนที่ด้วยโหนดใหม่. |

### ค่าที่ส่งคืน

ถ้า **node** แทนที่โหนดที่มีอยู่แล้วที่มีชื่อเดียวกัน โหนดเดิมจะถูกส่งคืน; หากไม่เช่นนั้น **nullptr** จะถูกส่งคืน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)