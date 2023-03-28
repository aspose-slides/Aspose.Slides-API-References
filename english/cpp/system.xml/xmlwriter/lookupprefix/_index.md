---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI.
type: docs
weight: 352
url: /cpp/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix([String](../../../system/string/)) method


When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ns | [String](../../../system/string/) | The namespace URI whose prefix you want to find. |

### Return Value

The matching prefix or **nullptr** if no matching namespace URI is found in the current scope.

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
