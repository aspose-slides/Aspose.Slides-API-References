---
title: ImageFlags
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje atrybuty danych pikseli reprezentowanych przez obiekt Image.
type: docs
weight: 274
url: /pl/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Reprezentuje atrybuty danych pikseli reprezentowanych przez obiekt [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Skalowalny. |
| HasAlpha | 2 | Zawiera informacje o alfabcie. |
| HasTranslucent | 4 | Istnieją wartości alfa większe niż 0 i mniejsze niż 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Dane pikseli są reprezentowane w przestrzeni kolorów RGB. |
| ColorSpaceCmyk | 32 | Dane pikseli są reprezentowane w przestrzeni kolorów CMYK. |
| ColorSpaceGray | 64 | Dane pikseli są w odcieniach szarości. |
| ColorSpaceYcbcr | 128 | Dane pikseli są reprezentowane w przestrzeni kolorów YCBCR. |
| ColorSpaceYcck | 256 | Dane pikseli są reprezentowane w przestrzeni kolorów YCCK. |
| HasRealDpi | 4096 | Informacje o DPI są przechowywane w obrazie. |
| HasRealPixelSize | 8192 | Rozmiar piksela jest przechowywany w obrazie. |
| ReadOnly | 65536 | Dane pikseli są tylko do odczytu. |
| Caching | 131072 | Może być buforowane w celu szybszego dostępu. |

## Zobacz także

* Przestrzeń nazw [System::Drawing::Imaging](../)
* Biblioteka [Aspose.Slides](../../)