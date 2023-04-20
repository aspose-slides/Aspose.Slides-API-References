---
title: ReadSubtree()
second_title: Aspose.Slides for C++ API Reference
description: Returns a new XmlReader instance that can be used to read the current node, and all its descendants.
type: docs
weight: 963
url: /cpp/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() method


Returns a new [XmlReader](../) instance that can be used to read the current node, and all its descendants.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### Return Value

A new XML reader instance set to [ReadState::Initial](../../readstate/). Calling the [XmlReader::Read](../read/) method positions the new reader on the node that was current before the call to the [XmlReader::ReadSubtree](./) method.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)