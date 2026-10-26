---
title: Zip64Mode
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wann ZIP64-Formatserweiterungen für eine OpenXML-Datei verwendet werden sollen.
type: docs
weight: 1119
url: /de/aspose.slides.export/zip64mode/
---
## Zip64Mode Aufzählung

Gibt an, wann ZIP64-Formatserweiterungen für eine OpenXML-Datei verwendet werden sollen.

```cpp
enum class Zip64Mode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Never | 0 | Verwenden Sie keine ZIP64-Formatserweiterungen. |
| IfNecessary | 1 | Verwenden Sie ZIP64-Formatserweiterungen, falls erforderlich. |
| Always | 2 | Verwenden Sie immer ZIP64-Formatserweiterungen. |

## Hinweise

Eine OpenXML-Datei ist ein ZIP-Archiv, das eine Grenze von 4 GB (2^32 Bytes) für die unverpackte Größe einer Datei, die komprimierte Größe einer Datei und die Gesamtausdehnung des Archivs hat, sowie ein Limit von 65.535 (2^16-1) Dateien im Archiv. ZIP64-Formatserweiterungen erhöhen die Grenzen auf 2^64.

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)