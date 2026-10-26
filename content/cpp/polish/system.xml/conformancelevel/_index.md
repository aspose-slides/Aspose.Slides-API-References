---
title: ConformanceLevel
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa poziom sprawdzania wejścia lub wyjścia, które wykonują obiekty XmlReader i XmlWriter.
type: docs
weight: 625
url: /pl/system.xml/conformancelevel/
---
## ConformanceLevel enum

Określa ilość sprawdzania wejścia lub wyjścia, które wykonują obiekty [XmlReader](../xmlreader/) i [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Auto | 0 | Obiekt [XmlReader](../xmlreader/) lub [XmlWriter](../xmlwriter/) automatycznie wykrywa, czy należy wykonać sprawdzanie na poziomie dokumentu, czy fragmentu, i wykonuje odpowiednie sprawdzanie. Jeśli opakowujesz inny obiekt [XmlReader](../xmlreader/) lub [XmlWriter](../xmlwriter/), obiekt zewnętrzny nie wykonuje dodatkowego sprawdzania zgodności. Sprawdzanie zgodności pozostaje po stronie leżącego u podstaw obiektu. |
| Fragment | 1 | Dane XML są [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) zgodnie z definicją W3C. Ten poziom zgodności reprezentuje dokument XML, który może nie mieć elementu głównego, ale jest poprawnie sformatowany. Ten poziom sprawdzania zapewnia, że strumień odczytywany lub zapisywany może być przetwarzany przez dowolny procesor jako [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Dane XML spełniają zasady poprawnie sformatowanego [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) określone przez W3C. Ten poziom sprawdzania zapewnia, że strumień odczytywany lub zapisywany może być przetwarzany przez dowolny procesor jako [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Zobacz także

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)