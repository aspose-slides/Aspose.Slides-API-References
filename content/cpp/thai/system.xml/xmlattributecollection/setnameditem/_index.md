---
title: SetNamedItem()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เพิ่ม XmlNode โดยใช้ผลลัพธ์ของ XmlNode::get_Name"
type: docs
weight: 14
url: /th/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) เมธอด

เพิ่ม [XmlNode](../../xmlnode/) โดยใช้ผลลัพธ์ของ [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | โหนดแอตทริบิวต์เพื่อเก็บในคอลเลกชันนี้ โหนดนี้จะสามารถเข้าถึงได้ในภายหลังโดยใช้ชื่อของโหนด หากโหนดที่มีชื่อนั้นอยู่แล้วในคอลเลกชัน จะถูกแทนที่ด้วยโหนดใหม่; มิฉะนั้น โหนดจะถูกเพิ่มต่อท้ายของคอลเลกชัน. |

### ค่าที่คืนกลับ

หาก **node** แทนที่โหนดที่มีอยู่แล้วซึ่งมีชื่อเดียวกัน โหนดเดิมจะถูกส่งกลับ; มิฉะนั้น โหนดที่เพิ่มเข้ามาจะถูกส่งกลับ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlAttributeCollection](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)