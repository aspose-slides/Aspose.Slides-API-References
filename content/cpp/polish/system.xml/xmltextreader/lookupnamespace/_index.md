---
title: LookupNamespace()
second_title: Aspose.Slides dla C++ – Referencja API
description: Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu.
type: docs
weight: 612
url: /pl/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) method


Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks, którego identyfikator URI przestrzeni nazw ma zostać rozwiązany. Aby dopasować domyślną przestrzeń nazw, przekaż pusty ciąg. Ten ciąg nie musi być atomizowany. |

### Wartość zwracana

Identyfikator URI przestrzeni nazw, do którego mapuje prefiks, lub **nullptr** jeśli nie znaleziono pasującego prefiksu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)