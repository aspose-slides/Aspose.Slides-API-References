---
title: get_NewParent()
second_title: مرجع API Aspose.Slides للـ C++
description: "يعيد قيمة XmlNode::get_ParentNode بعد إكمال العملية."
type: docs
weight: 40
url: /ar/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() طريقة


إرجاع قيمة [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) بعد إكمال العملية.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### قيمة الإرجاع

قيمة **ParentNode** بعد إكمال العملية. تُرجع هذه الطريقة **nullptr** إذا كان يتم إزالة العقدة. بالنسبة لعقد السمات، تُرجع هذه الطريقة قيمة [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlNode](../../xmlnode/)
* الفئة [XmlNodeChangedEventArgs](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)