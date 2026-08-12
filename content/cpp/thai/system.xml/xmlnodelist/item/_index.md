---
title: Item()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ดึงโหนดจากตำแหน่งที่กำหนด.
type: docs
weight: 14
url: /th/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) เมธอด


ดึงโหนดที่ตำแหน่งที่กำหนด.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มต้นจากศูนย์ในรายการของโหนด. |

### ค่าที่ส่งกลับ

[XmlNode](../../xmlnode/) ที่มีดัชนีที่ระบุในคอลเลกชัน. หาก **index** มากกว่าหรือเท่ากับจำนวนโหนดในรายการนี้ จะคืนค่า **nullptr**.

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlNodeList](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)