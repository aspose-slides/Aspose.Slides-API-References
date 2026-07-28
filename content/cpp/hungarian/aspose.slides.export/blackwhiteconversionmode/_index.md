---
title: BlackWhiteConversionMode
second_title: Aspose.Slides for C++ API-referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogy a diák képei hogyan lesznek konvertálva bitonális képekké.
type: docs
weight: 820
url: /hu/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Lehetőségeket biztosít, amelyek szabályozzák, hogy a diák képei hogyan lesznek konvertálva bitonális képekké.

```cpp
enum class BlackWhiteConversionMode
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Default | 0 | Nem ad meg konverziós algoritmust. A TIFF kodekben megvalósított algoritmus lesz használva. (Default) |
| Dithering | 1 | Megadja a dither algoritmust (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Megadja a Floyd-Steinberg dithering algoritmust. |
| Auto | 3 | Megadja az automatikusan kiszámolt küszöb algoritmust (Otsu). |
| AutoOtsu | 4 | Megadja az automatikusan kiszámolt Otsu küszöb algoritmusát. |
| Threshold25 | 5 | Megadja a statikus küszöb algoritmust (25%). |
| Threshold50 | 6 | Megadja a statikus küszöb algoritmust (50%). |
| Threshold75 | 7 | Megadja a statikus küszöb algoritmust (75%). |

## Lásd még

* Névtere [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)