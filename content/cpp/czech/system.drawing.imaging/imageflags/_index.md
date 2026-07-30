---
title: ImageFlags
second_title: Aspose.Slides pro C++ API Reference
description: Představuje atributy pixelových dat reprezentovaných objektem Image.
type: docs
weight: 274
url: /cs/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Představuje atributy pixelových dat reprezentovaných objektem [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Hodnoty

| Name | Value | Description |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Škálovatelné. |
| HasAlpha | 2 | Obsahuje informaci alfa. |
| HasTranslucent | 4 | Existují hodnoty alfa větší než 0 a menší než 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Pixelová data jsou reprezentována v barvovém prostoru RGB. |
| ColorSpaceCmyk | 32 | Pixelová data jsou reprezentována v barvovém prostoru CMYK. |
| ColorSpaceGray | 64 | Pixelová data jsou černobílá. |
| ColorSpaceYcbcr | 128 | Pixelová data jsou reprezentována v barvovém prostoru YCBCR. |
| ColorSpaceYcck | 256 | Pixelová data jsou reprezentována v barvovém prostoru YCCK. |
| HasRealDpi | 4096 | Informace o DPI jsou uloženy v obrázku. |
| HasRealPixelSize | 8192 | Velikost pixelu je uložena v obrázku. |
| ReadOnly | 65536 | Pixelová data jsou pouze pro čtení. |
| Caching | 131072 | Může být ukládáno do mezipaměti pro rychlejší přístup. |

## Viz také

* Jmenný prostor [System::Drawing::Imaging](../)
* Knihovna [Aspose.Slides](../../)