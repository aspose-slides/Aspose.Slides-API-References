---
title: CompressionLevel
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ZIP-Komprimierungsstufen für OpenXML-Datei an. Höhere Stufen bieten bessere Kompression auf Kosten einer langsameren Verarbeitung.
type: docs
weight: 846
url: /de/aspose.slides.export/compressionlevel/
---
## CompressionLevel Enum

Gibt ZIP-Komprimierungsstufen für OpenXML-Dateien an. Höhere Stufen bieten bessere Kompression auf Kosten einer langsameren Verarbeitung.

```cpp
enum class CompressionLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Keine Kompression wird angewendet. Dateien werden unverändert gespeichert. |
| Level1 | 1 | Schnellste Kompression mit dem niedrigsten Kompressionsverhältnis. |
| Level2 | 2 | Schnellere Kompression mit leicht besserem Kompressionsverhältnis als [CompressionLevel::Level1](./). |
| Level3 | 3 | Bietet bessere Kompression als [CompressionLevel::Level2](./) bei moderatem Leistungseinfluss. |
| Level4 | 4 | Bietet bessere Kompression als [CompressionLevel::Level3](./). |
| Level5 | 5 | Bietet verbesserte Kompression gegenüber [CompressionLevel::Level4](./) mit zusätzlicher Verarbeitungszeit. |
| Level6 | 6 | Standardkompression, die ein gutes Gleichgewicht zwischen Kompressionsgeschwindigkeit und Dateigröße bietet. Die Standard-Komprimierungsstufe. |
| Level7 | 7 | Bietet höhere Kompression als [CompressionLevel::Level6](./) bei langsamerer Verarbeitung. |
| Level8 | 8 | Bietet höhere Kompression als [CompressionLevel::Level7](./). |
| Level9 | 9 | Maximale Kompression. Produziert die kleinste Dateigröße bei der langsamsten Verarbeitungsgeschwindigkeit. |

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)