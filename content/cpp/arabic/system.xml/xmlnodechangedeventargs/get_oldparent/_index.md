---
title: get_OldParent()
second_title: مرجع API Aspose.Slides للغة C++
description: "يعيد قيمة XmlNode::get_ParentNode قبل بدء العملية."
type: docs
weight: 27
url: /ar/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() طريقة

يعيد القيمة الخاصة بـ [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) قبل بدء العملية.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### قيمة الإرجاع

قيمة **ParentNode** قبل بدء العملية. تُعيد هذه الطريقة **nullptr** إذا لم يكن للعقدة أب. بالنسبة لعقد السمات، تُعيد هذه الطريقة قيمة [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)