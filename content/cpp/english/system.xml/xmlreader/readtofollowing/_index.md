---
title: ReadToFollowing()
second_title: Aspose.Slides for C++ API Reference
description: Reads until an element with the specified qualified name is found.
type: docs
weight: 898
url: /system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) method


Reads until an element with the specified qualified name is found.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the element. |

### Return Value

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## XmlReader::ReadToFollowing(String, String) method


Reads until an element with the specified local name and namespace URI is found.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Return Value

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)