---
title: DateTimeStyles
second_title: Aspose.Slides för C++ API-referens
description: Definierar alternativ för datum- och tidsformatering. Bitflaggor.
type: docs
weight: 456
url: /sv/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Definierar alternativ för datum- och tidsformatering. Bitflaggor.

```cpp
enum class DateTimeStyles : int32_t
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Standard. |
| AllowLeadingWhite | 1 | Ignorera ledande blanksteg. |
| AllowTrailingWhite | 2 | Ignorera efterföljande blanksteg. |
| AllowInnerWhite | 4 | Ignorera inre blanksteg. |
| AllowWhiteSpaces | n/a | Ignorera alla blanksteg. |
| NoCurrentDateDefault | 8 | När en datum-/tidsträng analyseras, om alla år/månad/dag saknas, sätt standarddatumet till 0001/1/1 i stället för aktuellt år/månad/dag. |
| AdjustToUniversal | 16 | När en datum-/tidsträng analyseras, om en tidszonspecifikation (\"GMT\",\"Z\",\"+xxxx\",\"-xxxx\") finns, justerar vi den analyserade tiden till GMT. |
| AssumeLocal | 32 | Om ingen tidszon anges, använd den lokala tidszonen. |
| AssumeUniversal | 64 | Om ingen tidszon anges, använd UTC. |
| RoundtripKind | 128 | Försök bevara om indatan är ospecificerad, lokal eller UTC. |

## Se även

* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)