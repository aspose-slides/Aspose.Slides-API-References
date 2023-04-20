---
title: ReadNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates an XmlNode object based on the information in the XmlReader. The reader must be positioned on a node or attribute.
type: docs
weight: 495
url: /cpp/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) method


Creates an [XmlNode](../../xmlnode/) object based on the information in the [XmlReader](../../xmlreader/). The reader must be positioned on a node or attribute.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | The XML source. |

### Return Value

The new [XmlNode](../../xmlnode/) or **nullptr** if no more nodes exist.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)