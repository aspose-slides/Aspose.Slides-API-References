---
title: Zip64Mode
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, kiedy używać rozszerzeń formatu ZIP64 dla pliku OpenXML.
type: docs
weight: 1119
url: /pl/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Określa, kiedy używać rozszerzeń formatu ZIP64 dla pliku OpenXML.

```cpp
enum class Zip64Mode
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Never | 0 | Nie używaj rozszerzeń formatu ZIP64. |
| IfNecessary | 1 | Używaj rozszerzeń formatu ZIP64 w razie potrzeby. |
| Always | 2 | Zawsze używaj rozszerzeń formatu ZIP64. |

## Uwagi

OpenXML file jest archiwum ZIP, które ma limit 4 GB (2^32 bajtów) na niekompresowany rozmiar pliku, skompresowany rozmiar pliku oraz całkowity rozmiar archiwum, a także limit 65 535 (2^16-1) plików w archiwum. Rozszerzenia formatu ZIP64 zwiększają limity do 2^64.

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)