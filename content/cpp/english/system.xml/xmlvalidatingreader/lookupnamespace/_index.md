---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Reference
description: Resolves a namespace prefix in the current element's scope.
type: docs
weight: 547
url: /system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) method


Resolves a namespace prefix in the current element's scope.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix whose namespace Uniform Resource Identifier (URI) you want to resolve. To match the default namespace, pass an empty string. |

### Return Value

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)