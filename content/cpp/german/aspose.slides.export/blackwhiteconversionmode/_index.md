---
title: BlackWhiteConversionMode
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Optionen bereit, die steuern, wie die Bilder von Folien in bi-tonale Bilder konvertiert werden.
type: docs
weight: 820
url: /de/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode Enum

Stellt Optionen bereit, die steuern, wie die Bilder von Folien in bi-tonale Bilder konvertiert werden.

```cpp
enum class BlackWhiteConversionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | 0 | Gibt an, dass kein Konvertierungsalgorithmus verwendet wird. Der im TIFF-Codec implementierte Algorithmus wird verwendet. (Default) |
| Dithering | 1 | Gibt den Dithering-Algorithmus (Floyd-Steinberg) an. |
| DitheringFloydSteinberg | 2 | Gibt den Floyd-Steinberg-Dithering-Algorithmus an. |
| Auto | 3 | Gibt den automatisch berechneten Schwellenwert-Algorithmus (Otsu) an. |
| AutoOtsu | 4 | Gibt den automatisch berechneten Otsu-Schwellenwert-Algorithmus an. |
| Threshold25 | 5 | Gibt den statischen Schwellenwert-Algorithmus (25%) an. |
| Threshold50 | 6 | Gibt den statischen Schwellenwert-Algorithmus (50%) an. |
| Threshold75 | 7 | Gibt den statischen Schwellenwert-Algorithmus (75%) an. |

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)