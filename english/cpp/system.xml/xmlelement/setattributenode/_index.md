---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified XmlAttribute.
type: docs
weight: 261
url: /cpp/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode([SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlElement::SetAttributeNode([String](../../../system/string/), [String](../../../system/string/)) method


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
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
