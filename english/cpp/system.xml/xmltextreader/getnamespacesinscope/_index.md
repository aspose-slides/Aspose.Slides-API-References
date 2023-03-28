---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection that contains all namespaces currently in-scope.
type: docs
weight: 716
url: /cpp/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope([XmlNamespaceScope](../../xmlnamespacescope/)) method


Returns a collection that contains all namespaces currently in-scope.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | An XmlNamespaceScope value that specifies the type of namespace nodes to return. |

### Return Value

An IDictionary object that contains all the current in-scope namespaces. If the reader is not positioned on an element, an empty dictionary (no namespaces) is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
