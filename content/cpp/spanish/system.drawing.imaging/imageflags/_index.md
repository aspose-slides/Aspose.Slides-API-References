---
title: ImageFlags
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa los atributos de los datos de píxel representados por un objeto Image.
type: docs
weight: 274
url: /es/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Representa los atributos de los datos de píxel representados por un objeto [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Escalable. |
| HasAlpha | 2 | Contiene información alfa. |
| HasTranslucent | 4 | Hay valores alfa mayores que 0 y menores que 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Los datos de píxel se representan en el espacio de color RGB. |
| ColorSpaceCmyk | 32 | Los datos de píxel se representan en el espacio de color CMYK. |
| ColorSpaceGray | 64 | Los datos de píxel son en escala de grises. |
| ColorSpaceYcbcr | 128 | Los datos de píxel se representan en el espacio de color YCBCR. |
| ColorSpaceYcck | 256 | Los datos de píxel se representan en el espacio de color YCCK. |
| HasRealDpi | 4096 | La información DPI se almacena en la imagen. |
| HasRealPixelSize | 8192 | El tamaño de un píxel se almacena en la imagen. |
| ReadOnly | 65536 | Los datos de píxel son de solo lectura. |
| Caching | 131072 | Puede almacenarse en caché para un acceso más rápido. |

## Ver también

* Espacio de nombres [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)