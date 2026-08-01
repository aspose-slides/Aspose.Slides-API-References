---
title: DateTimeStyles
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert datum- en tijdopmaakopties. Bitvlaggen.
type: docs
weight: 456
url: /nl/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Definieert datum- en tijdopmaakopties. Bitvlaggen.

```cpp
enum class DateTimeStyles : int32_t
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Standaard. |
| AllowLeadingWhite | 1 | Negeer voorloopwitruimtes. |
| AllowTrailingWhite | 2 | Negeer volgende witruimtes. |
| AllowInnerWhite | 4 | Negeer interne witruimtes. |
| AllowWhiteSpaces | n/a | Negeer alle witruimtes. |
| NoCurrentDateDefault | 8 | Bij het parseren van een datum/tijd-string, als alle jaar/maand/dag ontbreken, stel de standaarddatum in op 0001/1/1 in plaats van het huidige jaar/maand/dag. |
| AdjustToUniversal | 16 | Bij het parseren van een datum/tijd-string, als er een tijdzone-specificatie ("GMT","Z","+xxxx","-xxxx") aanwezig is, passen we de geparseerde tijd aan op basis van GMT. |
| AssumeLocal | 32 | Als er geen tijdzone is opgegeven, gebruik dan de lokale tijdzone. |
| AssumeUniversal | 64 | Als er geen tijdzone is opgegeven, gebruik UTC. |
| RoundtripKind | 128 | Probeer te behouden of de invoer onbepaald, lokaal of UTC is. |

## Zie ook

* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)