---
title: get_LocalName()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, gets the local name of the current node.
type: docs
weight: 40
url: /cpp/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() method


When overridden in a derived class, gets the local name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Return Value

The name of the current node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**. For node types that do not have a name (like **[Text](../../../system.text/)**, **Comment**, and so on), this method returns [String::Empty](../../../system/string/empty/).

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)