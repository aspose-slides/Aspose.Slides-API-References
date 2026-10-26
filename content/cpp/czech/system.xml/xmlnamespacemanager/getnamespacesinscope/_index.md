---
title: GetNamespacesInScope()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací kolekci názvů jmenných prostorů klíčovaných prefixem, která může být použita k výčtu aktuálně platných jmenných prostorů.
type: docs
weight: 105
url: /cs/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) metoda

Vrací kolekci názvů jmenných prostorů klíčovaných prefixem, která může být použita k výčtu aktuálně platných jmenných prostorů.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Výčtová hodnota, která určuje typ uzlů jmenných prostorů, které mají být vráceny. |

### Návratová hodnota

Sbírka dvojic jmenných prostorů a prefixů, které jsou aktuálně v rozsahu.

## Viz také

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)