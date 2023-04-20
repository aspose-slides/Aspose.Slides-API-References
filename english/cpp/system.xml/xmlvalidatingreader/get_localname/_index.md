---
title: get_LocalName()
second_title: Aspose.Slides for C++ API Reference
description: Returns the local name of the current node.
type: docs
weight: 27
url: /cpp/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() method


Returns the local name of the current node.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### Return Value

The name of the current node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**. For node types that do not have a name (like **[Text](../../../system.text/)**, **Comment**, and so on), this method returns [String::Empty](../../../system/string/empty/).

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)