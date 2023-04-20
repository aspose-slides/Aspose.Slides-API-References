---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, resolves a namespace prefix in the current element's scope.
type: docs
weight: 729
url: /cpp/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) method


When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass an empty string. |

### Return Value

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)