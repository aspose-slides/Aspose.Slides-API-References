---
title: CreateElement()
second_title: Aspose.Slides for C++ API Reference
description: Creates an element with the specified name.
type: docs
weight: 339
url: /cpp/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) method


Creates an element with the specified name.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The qualified name of the element. If the name contains a colon then the [XmlNode::get_Prefix](../../xmlnode/get_prefix/) value reflects the part of the name preceding the colon and the [XmlDocument::get_LocalName](../get_localname/) value reflects the part of the name after the colon. The qualified name cannot include a prefix of **xmlns**. |

### Return Value

The new [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) method


Creates an [XmlElement](../../xmlelement/) with the qualified name and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | The qualified name of the element. If the name contains a colon then the [XmlNode::get_Prefix](../../xmlnode/get_prefix/) value will reflect the part of the name preceding the colon and the [XmlDocument::get_LocalName](../get_localname/) value will reflect the part of the name after the colon. The qualified name cannot include a prefix of **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the element. |

### Return Value

The new [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) method


Creates an element with the specified [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix of the new element (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. |
| localName | const [String](../../../system/string/)\& | The local name of the new element. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new element (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. |

### Return Value

The new [XmlElement](../../xmlelement/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)