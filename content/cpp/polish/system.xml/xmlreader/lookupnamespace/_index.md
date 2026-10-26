---
title: LookupNamespace()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu.
type: docs
weight: 729
url: /pl/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) metoda


Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks, którego URI przestrzeni nazw chcesz rozwiązać. Aby dopasować domyślną przestrzeń nazw, przekaż pusty łańcuch. |

### Wartość zwracana

URI przestrzeni nazw, do której mapowany jest prefiks, lub **nullptr**, jeśli nie znaleziono pasującego prefiksu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)