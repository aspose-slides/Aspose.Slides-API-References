---
title: GetAttributeNode()
second_title: Aspose.Slides for C++ API Reference
description: Returns the XmlAttribute with the specified name.
type: docs
weight: 248
url: /system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) method


Returns the [XmlAttribute](../../xmlattribute/) with the specified name.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of the attribute to retrieve. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

### Return Value

The specified [XmlAttribute](../../xmlattribute/) or **nullptr** if a matching attribute was not found.

## XmlElement::GetAttributeNode(String, String) method


Returns the [XmlAttribute](../../xmlattribute/) with the specified local name and namespace URI.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

The specified [XmlAttribute](../../xmlattribute/) or **nullptr** if a matching attribute was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)