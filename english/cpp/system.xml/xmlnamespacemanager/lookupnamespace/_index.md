---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Reference
description: Returns the namespace URI for the specified prefix.
type: docs
weight: 118
url: /cpp/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) method


Returns the namespace URI for the specified prefix.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass [String::Empty](../../../system/string/empty/). |

### Return Value

The namespace URI for **prefix** or **nullptr** if there is no mapped namespace. The returned string is atomized. For more information on atomized strings, see the [XmlNameTable](../../xmlnametable/) class.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)