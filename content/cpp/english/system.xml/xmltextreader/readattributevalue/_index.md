---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API Reference
description: Parses the attribute value into one or more Text, EntityReference, or EndEntity nodes.
type: docs
weight: 560
url: /system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() method


Parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### Return Value

**true** if there are nodes to return. **false** if the reader is not positioned on an attribute node when the initial call is made or if all the attribute values have been read. An empty attribute, such as, **misc=\"\"**, returns **true** with a single node with a value of [String::Empty](../../../system/string/empty/).

## See Also

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)