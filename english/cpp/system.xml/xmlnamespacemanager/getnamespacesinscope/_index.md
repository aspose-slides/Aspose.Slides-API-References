---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of namespace names keyed by prefix which can be used to enumerate the namespaces currently in scope.
type: docs
weight: 105
url: /cpp/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope([XmlNamespaceScope](../../xmlnamespacescope/)) method


Returns a collection of namespace names keyed by prefix which can be used to enumerate the namespaces currently in scope.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | An enumeration value that specifies the type of namespace nodes to return. |

### Return Value

A collection of namespace and prefix pairs currently in scope.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
