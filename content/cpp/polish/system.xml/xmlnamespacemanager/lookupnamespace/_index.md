---
title: LookupNamespace()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca URI przestrzeni nazw dla określonego prefiksu.
type: docs
weight: 118
url: /pl/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String&) metoda

Zwraca URI przestrzeni nazw dla określonego prefiksu.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks, którego URI przestrzeni nazw chcesz rozwiązać. Aby dopasować domyślną przestrzeń nazw, przekaż [String::Empty](../../../system/string/empty/). |

### Wartość zwracana

URI przestrzeni nazw dla **prefix** lub **nullptr**, jeśli nie istnieje skojarzona przestrzeń nazw. Zwrócony ciąg jest atomizowany. Aby uzyskać więcej informacji o atomizowanych ciągach, zobacz klasę [XmlNameTable](../../xmlnametable/).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNamespaceManager](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)