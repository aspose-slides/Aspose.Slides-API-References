---
title: ImageFlags
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft attributen van de pixelgegevens weer die door een Image-object worden gerepresenteerd.
type: docs
weight: 274
url: /nl/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Geeft attributen van de pixelgegevens weer die door een [Image](../../system.drawing/image/) object worden gerepresenteerd.

```cpp
enum class ImageFlags
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Schaalbaar. |
| HasAlpha | 2 | Bevat alfainformatie. |
| HasTranslucent | 4 | Er zijn alfawaarden groter dan 0 en kleiner dan 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | De pixeldataset wordt weergegeven in de RGB-kleurruimte. |
| ColorSpaceCmyk | 32 | De pixeldataset wordt weergegeven in de CMYK-kleurruimte. |
| ColorSpaceGray | 64 | De pixeldataset is grijswaarden. |
| ColorSpaceYcbcr | 128 | De pixeldataset wordt weergegeven in de YCBCR-kleurruimte. |
| ColorSpaceYcck | 256 | De pixeldataset wordt weergegeven in de YCCK-kleurruimte. |
| HasRealDpi | 4096 | De DPI-informatie wordt opgeslagen in de afbeelding. |
| HasRealPixelSize | 8192 | De grootte van een pixel wordt opgeslagen in de afbeelding. |
| ReadOnly | 65536 | De pixeldataset is alleen-lezen. |
| Caching | 131072 | Kan worden gecached voor snellere toegang. |

## Zie ook

* Naamruimte [System::Drawing::Imaging](../)
* Bibliotheek [Aspose.Slides](../../)