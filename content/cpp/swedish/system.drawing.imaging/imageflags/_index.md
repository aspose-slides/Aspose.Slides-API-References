---
title: ImageFlags
second_title: Aspose.Slides för C++ API-referens
description: Representerar attribut för pixeldata som representeras av ett Image-objekt.
type: docs
weight: 274
url: /sv/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Representerar egenskaper hos pixeldata som representeras av ett [Image](../../system.drawing/image/)-objekt.

```cpp
enum class ImageFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Skalbar. |
| HasAlpha | 2 | Innehåller alfa-information. |
| HasTranslucent | 4 | Det finns alfavärden som är större än 0 och mindre än 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Pixeldata representeras i RGB-färgrymden. |
| ColorSpaceCmyk | 32 | Pixeldata representeras i CMYK-färgrymden. |
| ColorSpaceGray | 64 | Pixeldata är gråskala. |
| ColorSpaceYcbcr | 128 | Pixeldata representeras i YCBCR-färgrymden. |
| ColorSpaceYcck | 256 | Pixeldata representeras i YCCK-färgrymden. |
| HasRealDpi | 4096 | DPI-informationen lagras i bilden. |
| HasRealPixelSize | 8192 | Pixelstorleken lagras i bilden. |
| ReadOnly | 65536 | Pixeldata är skrivskyddad. |
| Caching | 131072 | Kan cachas för snabbare åtkomst. |

## Se även

* Namnrymd [System::Drawing::Imaging](../)
* Bibliotek [Aspose.Slides](../../)