---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Creates an XmlAttribute with the specified name.
type: docs
weight: 274
url: /cpp/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method


Creates an [XmlAttribute](../../xmlattribute/) with the specified name.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The qualified name of the attribute. If the name contains a colon, the [XmlNode::get_Prefix](../../xmlnode/get_prefix/) value reflects the part of the name preceding the first colon and the [XmlDocument::get_LocalName](../get_localname/) value reflects the part of the name following the first colon. The [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) remains empty unless the prefix is a recognized built-in prefix such as **xmlns**. In this case get_NamespaceURI has a value of [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Return Value

The new [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) method


Creates an [XmlAttribute](../../xmlattribute/) with the specified qualified name and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | The qualified name of the attribute. If the name contains a colon then the [XmlNode::get_Prefix](../../xmlnode/get_prefix/) value will reflect the part of the name preceding the colon and the [XmlDocument::get_LocalName](../get_localname/) value will reflect the part of the name after the colon. |
| namespaceURI | const [String](../../../system/string/)\& | The namespaceURI of the attribute. If the qualified name includes a prefix of **xmlns**, then this parameter must be [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Return Value

The new [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method


Creates an [XmlAttribute](../../xmlattribute/) with the specified [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix of the attribute (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. |
| localName | const [String](../../../system/string/)\& | The local name of the attribute. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the attribute (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. If **prefix** is **xmlns**, then this parameter must be [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) otherwise an exception is thrown. |

### Return Value

The new [XmlAttribute](../../xmlattribute/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)