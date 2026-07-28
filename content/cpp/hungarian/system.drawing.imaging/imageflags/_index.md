---
title: ImageFlags
second_title: Aspose.Slides for C++ API Referencia
description: Az Image objektum által képviselt képpontadat attribútumait jelöli.
type: docs
weight: 274
url: /hu/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Az [Image](../../system.drawing/image/) objektum által képviselt képpontadat attribútumait jelöli.

```cpp
enum class ImageFlags
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Skálázható. |
| HasAlpha | 2 | Alfa információt tartalmaz. |
| HasTranslucent | 4 | 0-nál nagyobb és 255-nél kisebb alfa értékek vannak. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | A képpontadat RGB színterben van ábrázolva. |
| ColorSpaceCmyk | 32 | A képpontadat CMYK színterben van ábrázolva. |
| ColorSpaceGray | 64 | A képpontadat szürkeárnyalatos. |
| ColorSpaceYcbcr | 128 | A képpontadat YCBCR színterben van ábrázolva. |
| ColorSpaceYcck | 256 | A képpontadat YCCK színterben van ábrázolva. |
| HasRealDpi | 4096 | A DPI információ tárolva van a képen. |
| HasRealPixelSize | 8192 | A pixel mérete tárolva van a képen. |
| ReadOnly | 65536 | A képpontadat csak olvasható. |
| Caching | 131072 | Gyorsabb hozzáférés érdekében gyorsítótárazható. |

## Lásd még

* Névtere [System::Drawing::Imaging](../)
* Könyvtár [Aspose.Slides](../../)