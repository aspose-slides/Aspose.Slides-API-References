---
title: get_OldParent()
second_title: مرجع API Aspose.Slides برای C++
description: "مقدار XmlNode::get_ParentNode را قبل از شروع عملیات بر می‌گرداند."
type: docs
weight: 27
url: /fa/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() متد


مقدار [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) را قبل از شروع عملیات بر می‌گرداند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### مقدار بازگشتی

مقدار **ParentNode** قبل از شروع عملیات. این متد **nullptr** را بر می‌گرداند اگر گره والد نداشته باشد. برای گره‌های ویژگی، این متد مقدار [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) را بر می‌گرداند.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlNodeChangedEventArgs](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)