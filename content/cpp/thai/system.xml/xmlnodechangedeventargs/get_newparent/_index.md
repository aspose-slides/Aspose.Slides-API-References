---
title: get_NewParent()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ส่งคืนค่าของ XmlNode::get_ParentNode หลังจากการดำเนินการเสร็จสมบูรณ์."
type: docs
weight: 40
url: /th/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() เมธอด

ส่งคืนค่าของ [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) หลังจากการดำเนินการเสร็จสมบูรณ์.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### ค่าที่ส่งคืน

ค่าของ **ParentNode** หลังจากการดำเนินการเสร็จสมบูรณ์. เมธอดนี้ส่งคืน **nullptr** ถ้าโหนดกำลังถูกลบ. สำหรับโหนดแอตทริบิวต์, เมธอดนี้ส่งคืนค่า [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlNodeChangedEventArgs](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)