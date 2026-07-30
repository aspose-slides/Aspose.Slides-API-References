---
title: LookupPrefix()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vyhledá předponu deklarovanou pro dané URI jmenného prostoru.
type: docs
weight: 131
url: /cs/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) metoda

Vyhledá předponu deklarovanou pro zadaný URI jmenného prostoru.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Jmenný prostor, který má být vyřešen pro předponu. |

### Návratová hodnota

Odpovídající předpona. Pokud neexistuje žádná přiřazená předpona, metoda vrátí [String::Empty](../../../system/string/empty/). Pokud je zadána null hodnota, vrátí se **nullptr**.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNamespaceManager](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)