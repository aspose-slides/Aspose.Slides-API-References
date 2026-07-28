---
title: XmlDateTimeSerializationMode
second_title: Dokumentacja API Aspose.Slides dla C++
description: Określa, jak traktować wartość czasu przy konwertowaniu między łańcuchem znaków a DateTime.
type: docs
weight: 781
url: /pl/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode wyliczenie

Określa, jak traktować wartość czasu przy konwertowaniu między łańcuchem znaków a [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Local | 0 | Traktuj jako czas lokalny. Jeśli obiekt [DateTime](../../system/datetime/) reprezentuje Uniwersalny Czas Koordynowany (UTC), zostaje on przekonwertowany na czas lokalny. |
| Utc | 1 | Traktuj jako UTC. Jeśli obiekt [DateTime](../../system/datetime/) reprezentuje czas lokalny, zostaje on przekonwertowany na UTC. |
| Unspecified | 2 | Traktuj jako czas lokalny, jeśli [DateTime](../../system/datetime/) jest konwertowany na łańcuch znaków. Jeśli łańcuch znaków jest konwertowany na [DateTime](../../system/datetime/), konwertuj na czas lokalny, jeśli określono strefę czasową. |
| RoundtripKind | 3 | Informacje o strefie czasowej powinny być zachowane podczas konwersji. |

## Zobacz również

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)