---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Reference
description: Resolves a namespace prefix in the current element's scope.
type: docs
weight: 612
url: /system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) method


Resolves a namespace prefix in the current element's scope.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass an empty string. This string does not have to be atomized. |

### Return Value

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)