---
title: IsStartElement()
second_title: Aspose.Slides for C++ API Reference
description: "Calls XmlReader::MoveToContent and tests if the current content node is a start tag or empty element tag."
type: docs
weight: 885
url: /system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method


Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### Return Value

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## XmlReader::IsStartElement(String) method


Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](../get_name/) value of the element found matches the given argument.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The string matched against the **Name** value of the element found. |

### Return Value

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## XmlReader::IsStartElement(String, String) method


Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found match the given strings.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | The string to match against the **LocalName** value of the element found. |
| ns | [String](../../../system/string/) | The string to match against the **NamespaceURI** value of the element found. |

### Return Value

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## See Also

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)