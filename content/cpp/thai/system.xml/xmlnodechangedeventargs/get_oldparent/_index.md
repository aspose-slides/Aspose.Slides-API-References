---
title: get_OldParent()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คืนค่าของ XmlNode::get_ParentNode ก่อนที่การดำเนินการจะเริ่มต้น."
type: docs
weight: 27
url: /th/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() เมธอด


คืนค่าของ [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) ก่อนที่การดำเนินการจะเริ่มต้น.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### ค่าที่ส่งกลับ

ค่าของ **ParentNode** ก่อนที่การดำเนินการจะเริ่มต้น. เมธอดนี้คืนค่า **nullptr** หากโหนดไม่มีผู้ปกครอง. สำหรับโหนดแอตทริบิวต์, เมธอดนี้คืนค่า [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [XmlNodeChangedEventArgs](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)