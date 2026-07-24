---
title: ImageFlags
second_title: Aspose.Slides for C++ API Referansı
description: Bir Image nesnesi tarafından temsil edilen piksel verisinin özniteliklerini temsil eder.
type: docs
weight: 274
url: /tr/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Represents attributes of the pixel data represented by an [Image](../../system.drawing/image/) object.

```cpp
enum class ImageFlags
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Ölçeklenebilir. |
| HasAlpha | 2 | Alfa bilgisi içerir. |
| HasTranslucent | 4 | 0'dan büyük ve 255'ten küçük alfa değerleri vardır. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Piksel verisi RGB renk uzayında temsil edilir. |
| ColorSpaceCmyk | 32 | Piksel verisi CMYK renk uzayında temsil edilir. |
| ColorSpaceGray | 64 | Piksel verisi gri tonlamalıdır. |
| ColorSpaceYcbcr | 128 | Piksel verisi YCBCR renk uzayında temsil edilir. |
| ColorSpaceYcck | 256 | Piksel verisi YCCK renk uzayında temsil edilir. |
| HasRealDpi | 4096 | DPI bilgisi görüntüde depolanır. |
| HasRealPixelSize | 8192 | Bir pikselin boyutu görüntüde depolanır. |
| ReadOnly | 65536 | Piksel verisi yalnızca okunabilir. |
| Caching | 131072 | Daha hızlı erişim için önbelleğe alınabilir. |

## İlgili

* Ad alanı [System::Drawing::Imaging](../)
* Kütüphane [Aspose.Slides](../../)