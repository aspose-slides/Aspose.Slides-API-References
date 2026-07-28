---
title: DateTimeStyles
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a dátum és idő formázási beállításait. Bitjelzők.
type: docs
weight: 456
url: /hu/system.globalization/datetimestyles/
---
## DateTimeStyles enumeráció

Defines date and time formatting options. Bit flags.

```cpp
enum class DateTimeStyles : int32_t
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Alapértelmezett. |
| AllowLeadingWhite | 1 | Figyelmen kívül hagyja a kezdő szóközöket. |
| AllowTrailingWhite | 2 | Figyelmen kívül hagyja a záró szóközöket. |
| AllowInnerWhite | 4 | Figyelmen kívül hagyja a belső szóközöket. |
| AllowWhiteSpaces | n/a | Figyelmen kívül hagyja az összes szóközt. |
| NoCurrentDateDefault | 8 | Dátum/idő karakterlánc feldolgozásakor, ha az év/hónap/nap hiányzik, az alapértelmezett dátumot 0001/1/1-re állítja, a jelenlegi év/hónap/nap helyett. |
| AdjustToUniversal | 16 | Dátum/idő karakterlánc feldolgozásakor, ha időzóna megadás (\"GMT\",\"Z\",\"+xxxx\",\"-xxxx\") van, a feldolgozott időt GMT-hez igazítjuk. |
| AssumeLocal | 32 | Ha nincs megadva időzóna, a helyi időzónát használja. |
| AssumeUniversal | 64 | Ha nincs megadva időzóna, az UTC-t használja. |
| RoundtripKind | 128 | Megkísérli megőrizni, hogy a bemenet nincs megadva, helyi vagy UTC. |

## Lásd még

* Névtér [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)