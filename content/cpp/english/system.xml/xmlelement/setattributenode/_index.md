---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified XmlAttribute.
type: docs
weight: 261
url: /system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Adds the specified [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | The [XmlAttribute](../../xmlattribute/) node to add to the attribute collection for this element. |

### Return Value

If the attribute replaces an existing attribute with the same name, the old [XmlAttribute](../../xmlattribute/) is returned; otherwise, **nullptr** is returned.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The **newAttr** was created from a different document than the one that created this node. Or this node is read-only. |
| InvalidOperationException | The **newAttr** is already an attribute of another [XmlElement](../) object. You must explicitly clone [XmlAttribute](../../xmlattribute/) nodes to re-use them in other [XmlElement](../) objects. |


## XmlElement::SetAttributeNode(String, String) method


Adds the specified [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

The [XmlAttribute](../../xmlattribute/) to add.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)