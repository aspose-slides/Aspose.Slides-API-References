---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API Reference
description: Finds the prefix declared for the given namespace URI.
type: docs
weight: 131
url: /cpp/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) method


Finds the prefix declared for the given namespace URI.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | The namespace to resolve for the prefix. |

### Return Value

The matching prefix. If there is no mapped prefix, the method returns [String::Empty](../../../system/string/empty/). If a null value is supplied, then **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)