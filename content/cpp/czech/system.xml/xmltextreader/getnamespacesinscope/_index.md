---
title: GetNamespacesInScope()
second_title: Aspose.Slides pro C++ - reference API
description: Vrací kolekci, která obsahuje všechny aktuálně platné jmenné prostory.
type: docs
weight: 716
url: /cs/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) metoda

Vrací kolekci, která obsahuje všechny aktuálně platné jmenné prostory.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Hodnota XmlNamespaceScope, která určuje typ uzlů jmenných prostorů, které mají být vráceny. |

### Návratová hodnota

Objekt IDictionary, který obsahuje všechny aktuálně platné jmenné prostory. Pokud čtečka není umístěna na element, vrátí se prázdný slovník (žádné jmenné prostory).

## Viz také

* Výčet [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDictionary](../../../system.collections.generic/idictionary/)
* Třída [String](../../../system/string/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)