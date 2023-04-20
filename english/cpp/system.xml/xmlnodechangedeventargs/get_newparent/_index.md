---
title: get_NewParent()
second_title: Aspose.Slides for C++ API Reference
description: "Returns the value of the XmlNode::get_ParentNode after the operation completes."
type: docs
weight: 40
url: /cpp/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() method


Returns the value of the [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) after the operation completes.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### Return Value

The value of the **ParentNode** after the operation completes. This method returns **nullptr** if the node is being removed. For attribute nodes, this method returns the [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)