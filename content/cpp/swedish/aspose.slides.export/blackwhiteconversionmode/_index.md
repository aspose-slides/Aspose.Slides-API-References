---
title: BlackWhiteConversionMode
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller alternativ som styr hur bildspelsbilder konverteras till bitonala bilder.
type: docs
weight: 820
url: /sv/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Tillhandahåller alternativ som styr hur bildspelens bilder konverteras till bitonala bilder.

```cpp
enum class BlackWhiteConversionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | 0 | Anger ingen konverteringsalgoritm. Algoritmen som implementerats i TIFF-codec kommer att användas. (Standard) |
| Dithering | 1 | Anger dithering-algoritmen (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Anger Floyd-Steinberg-ditheringalgoritmen. |
| Auto | 3 | Anger den automatiskt beräknade tröskelalgoritmen (Otsu). |
| AutoOtsu | 4 | Anger den automatiskt beräknade Otsus tröskelalgoritm. |
| Threshold25 | 5 | Anger den statiska tröskelalgoritmen (25%). |
| Threshold50 | 6 | Anger den statiska tröskelalgoritmen (50%). |
| Threshold75 | 7 | Anger den statiska tröskelalgoritmen (75%). |

## Se även

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)