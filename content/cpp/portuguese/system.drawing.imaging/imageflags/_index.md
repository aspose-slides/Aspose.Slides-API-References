---
title: ImageFlags
second_title: Referência da API Aspose.Slides para C++
description: Representa os atributos dos dados de pixel representados por um objeto Image.
type: docs
weight: 274
url: /pt/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Representa atributos dos dados de pixel representados por um objeto [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Escalável. |
| HasAlpha | 2 | Contém informação alfa. |
| HasTranslucent | 4 | Existem valores alfa maiores que 0 e menores que 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Os dados de pixel são representados no espaço de cores RGB. |
| ColorSpaceCmyk | 32 | Os dados de pixel são representados no espaço de cores CMYK. |
| ColorSpaceGray | 64 | Os dados de pixel são em tons de cinza. |
| ColorSpaceYcbcr | 128 | Os dados de pixel são representados no espaço de cores YCBCR. |
| ColorSpaceYcck | 256 | Os dados de pixel são representados no espaço de cores YCCK. |
| HasRealDpi | 4096 | As informações de DPI são armazenadas na imagem. |
| HasRealPixelSize | 8192 | O tamanho de um pixel é armazenado na imagem. |
| ReadOnly | 65536 | Os dados de pixel são somente leitura. |
| Caching | 131072 | Pode ser armazenado em cache para acesso mais rápido. |

## Veja Também

* Namespace [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)