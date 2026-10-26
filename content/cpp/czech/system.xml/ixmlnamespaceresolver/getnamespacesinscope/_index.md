---
title: GetNamespacesInScope()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací kolekci definovaných mapování prefix-namespace, která jsou aktuálně v rozsahu.
type: docs
weight: 1
url: /cs/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) metoda


Vrací kolekci definovaných mapování prefix-namespace, která jsou aktuálně v rozsahu.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Hodnota XmlNamespaceScope, která určuje typ uzlů jmenného prostoru, které se mají vrátit. |

### Návratová hodnota

Kolekce IDictionary, která obsahuje aktuální jmenné prostory v rozsahu.

## Viz také

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDictionary](../../../system.collections.generic/idictionary/)
* Třída [String](../../../system/string/)
* Třída [IXmlNamespaceResolver](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)