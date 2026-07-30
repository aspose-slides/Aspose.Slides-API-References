---
title: DateTimeStyles
second_title: Aspose.Slides pro C++ API Reference
description: Definuje možnosti formátování data a času. Bitové příznaky.
type: docs
weight: 456
url: /cs/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Definuje možnosti formátování data a času. Bitové příznaky.

```cpp
enum class DateTimeStyles : int32_t
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Výchozí. |
| AllowLeadingWhite | 1 | Ignorovat úvodní bílé znaky. |
| AllowTrailingWhite | 2 | Ignorovat koncové bílé znaky. |
| AllowInnerWhite | 4 | Ignorovat vnitřní bílé znaky. |
| AllowWhiteSpaces | n/a | Ignorovat všechny bílé znaky. |
| NoCurrentDateDefault | 8 | Při parsování řetězce data/času, pokud chybí celý rok/měsíc/den, nastaví výchozí datum na 0001/1/1 místo aktuálního roku/měsíce/dne. |
| AdjustToUniversal | 16 | Při parsování řetězce data/času, pokud existuje specifikátor časové zóny (\"GMT\",\"Z\",\"+xxxx\", \"-xxxx\"), upravíme analyzovaný čas na GMT. |
| AssumeLocal | 32 | Pokud není zadána žádná časová zóna, použije se místní časová zóna. |
| AssumeUniversal | 64 | Pokud není zadána žádná časová zóna, použije se UTC. |
| RoundtripKind | 128 | Pokusí se zachovat, zda je vstup nespecifikovaný, místní nebo UTC. |

## Viz také

* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)