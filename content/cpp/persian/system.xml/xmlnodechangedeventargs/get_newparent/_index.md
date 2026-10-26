---
title: get_NewParent()
second_title: Aspose.Slides برای API مرجع C++
description: "مقدار XmlNode::get_ParentNode را پس از اتمام عملیات برمی‌گرداند."
type: docs
weight: 40
url: /fa/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() متد

مقدار [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) را پس از اتمام عملیات برمی‌گرداند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### مقدار بازگشت

مقدار **ParentNode** پس از اتمام عملیات. این متد **nullptr** را برمی‌گرداند اگر گره در حال حذف باشد. برای گره‌های صفت، این متد مقدار [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) را برمی‌گرداند.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)