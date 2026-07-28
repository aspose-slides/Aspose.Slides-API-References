---
title: DateTimeStyles
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Definiuje opcje formatowania daty i czasu. Flagi bitowe.
type: docs
weight: 456
url: /pl/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Defines date and time formatting options. Bit flags.

```cpp
enum class DateTimeStyles : int32_t
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Domyślnie. |
| AllowLeadingWhite | 1 | Ignoruj początkowe białe znaki. |
| AllowTrailingWhite | 2 | Ignoruj końcowe białe znaki. |
| AllowInnerWhite | 4 | Ignoruj wewnętrzne białe znaki. |
| AllowWhiteSpaces | n/a | Ignoruj wszystkie białe znaki. |
| NoCurrentDateDefault | 8 | Podczas analizowania ciągu daty/godziny, jeśli brak wszystkich elementów rok/miesiąc/dzień, ustaw domyślną datę na 0001/1/1, zamiast bieżącego roku/miesiąca/dnia. |
| AdjustToUniversal | 16 | Podczas analizowania ciągu daty/godziny, jeśli obecny jest specyfikator strefy czasowej ("GMT","Z","+xxxx","-xxxx"), dostosujemy parsowany czas do GMT. |
| AssumeLocal | 32 | Jeśli nie podano strefy czasowej, użyj lokalnej strefy. |
| AssumeUniversal | 64 | Jeśli nie podano strefy czasowej, użyj UTC. |
| RoundtripKind | 128 | Spróbuj zachować informację, czy wejście było nieokreślone, lokalne czy UTC. |

## Zobacz także

* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)