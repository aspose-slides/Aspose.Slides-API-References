---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ API Reference
description: Advances the XmlReader to the next descendant element with the specified qualified name.
type: docs
weight: 911
url: /cpp/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) method


Advances the [XmlReader](../) to the next descendant element with the specified qualified name.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the element you wish to move to. |

### Return Value

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## XmlReader::ReadToDescendant(String, String) method


Advances the [XmlReader](../) to the next descendant element with the specified local name and namespace URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element you wish to move to. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element you wish to move to. |

### Return Value

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String,String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)