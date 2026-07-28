---
title: LookupNamespace()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu.
type: docs
weight: 404
url: /pl/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) metoda

Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks, którego URI przestrzeni nazw chcesz rozwiązać. Aby dopasować domyślną przestrzeń nazw, przekaż pusty ciąg znaków. Ten ciąg nie musi być atomizowany. |

### Wartość zwracana

URI przestrzeni nazw, do którego mapuje prefiks, lub **nullptr** jeśli nie znaleziono pasującego prefiksu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)