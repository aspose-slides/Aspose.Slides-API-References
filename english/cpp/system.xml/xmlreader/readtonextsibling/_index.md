---
title: ReadToNextSibling()
second_title: Aspose.Slides for C++ API Reference
description: Advances the XmlReader to the next sibling element with the specified qualified name.
type: docs
weight: 924
url: /cpp/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling([String](../../../system/string/)) method


Advances the [XmlReader](../) to the next sibling element with the specified qualified name.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the sibling element you wish to move to. |

### Return Value

**true** if a matching sibling element is found; otherwise **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlReader::ReadToNextSibling([String](../../../system/string/), [String](../../../system/string/)) method


Advances the [XmlReader](../) to the next sibling element with the specified local name and namespace URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the sibling element you wish to move to. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the sibling element you wish to move to. |

### Return Value

**true** if a matching sibling element is found; otherwise, **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
