---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: "Returns the first child element with the specified XmlNode::get_Name."
type: docs
weight: 586
url: /system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) method


Returns the first child element with the specified [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the element to retrieve. |

### Return Value

The first [XmlElement](../../xmlelement/) that matches the specified name. It returns **nullptr** if there is no match.

## XmlNode::idx_get(String, String) method


Returns the first child element with the specified [XmlNode::get_LocalName](../get_localname/) and [XmlNode::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | The local name of the element. |
| ns | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

The first [XmlElement](../../xmlelement/) with the matching **localname** and **ns**. It returns **nullptr** if there is no match.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)