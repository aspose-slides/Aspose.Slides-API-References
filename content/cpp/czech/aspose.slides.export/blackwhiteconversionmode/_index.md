---
title: BlackWhiteConversionMode
second_title: Aspose.Slides pro C++ - reference API
description: Poskytuje možnosti, které řídí, jak budou obrázky snímků konvertovány na bitonální obrázky.
type: docs
weight: 820
url: /cs/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Poskytuje možnosti, které řídí, jak budou obrázky snímků konvertovány na bitonální obrázky.

```cpp
enum class BlackWhiteConversionMode
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Default | 0 | Určuje, že se nepoužije žádný konverzní algoritmus. Bude použit algoritmus implementovaný v kodeku TIFF. (Default) |
| Dithering | 1 | Určuje algoritmus rozptylování (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Určuje algoritmus rozptylování Floyd-Steinberg. |
| Auto | 3 | Určuje automaticky vypočítaný algoritmus prahování (Otsu). |
| AutoOtsu | 4 | Určuje automaticky vypočítaný Otsuův algoritmus prahování. |
| Threshold25 | 5 | Určuje statický algoritmus prahování (25%). |
| Threshold50 | 6 | Určuje statický algoritmus prahování (50%). |
| Threshold75 | 7 | Určuje statický algoritmus prahování (75%). |

## Viz také

* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)