---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of defined prefix-namespace mappings that are currently in scope.
type: docs
weight: 1
url: /system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) method


Returns a collection of defined prefix-namespace mappings that are currently in scope.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | An XmlNamespaceScope value that specifies the type of namespace nodes to return. |

### Return Value

An IDictionary collection that contains the current in-scope namespaces.

## See Also

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)