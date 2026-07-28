---
title: LookupNamespace()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca URI przestrzeni nazw dla określonego prefiksu.
type: docs
weight: 404
url: /pl/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metoda

Zwraca URI przestrzeni nazw dla określonego prefiksu.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks, którego URI przestrzeni nazw ma być rozwiązane. Aby dopasować domyślną przestrzeń nazw, przekaż [String::Empty](../../../system/string/empty/). |

### Wartość zwracana

Obiekt [String](../../../system/string/) zawierający URI przestrzeni nazw przypisany do określonego prefiksu; **nullptr**, jeśli żaden URI nie jest przypisany do podanego prefiksu. Zwrócony [String](../../../system/string/) jest atomizowany.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)