---
title: BlackWhiteConversionMode
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona opciones que controlan cómo se convertirán las imágenes de las diapositivas a imágenes bitonales.
type: docs
weight: 820
url: /es/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Proporciona opciones que controlan cómo se convertirán las imágenes de las diapositivas a imágenes bitonales.

```cpp
enum class BlackWhiteConversionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | 0 | Especifica que no hay algoritmo de conversión. El algoritmo implementado en el códec TIFF se usará. (Default) |
| Dithering | 1 | Especifica el algoritmo de tramado (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Especifica el algoritmo de tramado Floyd-Steinberg. |
| Auto | 3 | Especifica el algoritmo de umbral calculado automáticamente (Otsu). |
| AutoOtsu | 4 | Especifica el algoritmo de umbral Otsu calculado automáticamente. |
| Threshold25 | 5 | Especifica el algoritmo de umbral estático (25%). |
| Threshold50 | 6 | Especifica el algoritmo de umbral estático (50%). |
| Threshold75 | 7 | Especifica el algoritmo de umbral estático (75%). |

## Véase también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)