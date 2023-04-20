---
title: RemoveAttributeNode()
second_title: Aspose.Slides for C++ API Reference
description: Removes the specified XmlAttribute.
type: docs
weight: 274
url: /cpp/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method


Removes the specified [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | The [XmlAttribute](../../xmlattribute/) node to remove. If the removed attribute has a default value, it is immediately replaced. |

### Return Value

The removed [XmlAttribute](../../xmlattribute/) or **nullptr** if **oldAttr** is not an attribute node of the [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) method


Removes the [XmlAttribute](../../xmlattribute/) specified by the local name and namespace URI. (If the removed attribute has a default value, it is immediately replaced).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

The removed [XmlAttribute](../../xmlattribute/) or **nullptr** if the [XmlElement](../) does not have a matching attribute node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)