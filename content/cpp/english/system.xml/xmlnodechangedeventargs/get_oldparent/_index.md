---
title: get_OldParent()
second_title: Aspose.Slides for C++ API Reference
description: "Returns the value of the XmlNode::get_ParentNode before the operation began."
type: docs
weight: 27
url: /system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() method


Returns the value of the [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) before the operation began.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### Return Value

The value of the **ParentNode** before the operation began. This method returns **nullptr** if the node did not have a parent. For attribute nodes, this method returns the [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)