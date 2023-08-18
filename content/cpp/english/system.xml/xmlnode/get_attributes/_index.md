---
title: get_Attributes()
second_title: Aspose.Slides for C++ API Reference
description: Returns an XmlAttributeCollection containing the attributes of this node.
type: docs
weight: 105
url: /system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() method


Returns an [XmlAttributeCollection](../../xmlattributecollection/) containing the attributes of this node.

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```


### Return Value

An [XmlAttributeCollection](../../xmlattributecollection/) containing the attributes of the node. If the node is of type [XmlNodeType::Element](../../xmlnodetype/), the attributes of the node are returned. Otherwise, this method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttributeCollection](../../xmlattributecollection/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)