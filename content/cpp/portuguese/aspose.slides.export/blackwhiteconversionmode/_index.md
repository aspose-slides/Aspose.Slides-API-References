---
title: BlackWhiteConversionMode
second_title: Referência da API Aspose.Slides para C++
description: Fornece opções que controlam como as imagens dos slides serão convertidas em imagens bitonais.
type: docs
weight: 820
url: /pt/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Fornece opções que controlam como as imagens dos slides serão convertidas em imagens bitonais.

```cpp
enum class BlackWhiteConversionMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Default | 0 | Especifica nenhum algoritmo de conversão. O algoritmo implementado no codec TIFF será usado. (Default) |
| Dithering | 1 | Especifica o algoritmo de dithering (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Especifica o algoritmo de dithering Floyd-Steinberg. |
| Auto | 3 | Especifica o algoritmo de limiar calculado automaticamente (Otsu). |
| AutoOtsu | 4 | Especifica o algoritmo de limiar de Otsu calculado automaticamente. |
| Threshold25 | 5 | Especifica o algoritmo de limiar estático (25%). |
| Threshold50 | 6 | Especifica o algoritmo de limiar estático (50%). |
| Threshold75 | 7 | Especifica o algoritmo de limiar estático (75%). |

## Ver Também

* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)