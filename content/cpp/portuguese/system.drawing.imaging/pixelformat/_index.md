---
title: PixelFormat
second_title: Referência da API Aspose.Slides para C++
description: Especifica o formato dos dados de cor de um pixel.
type: docs
weight: 326
url: /pt/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Especifica o formato dos dados de cor de um pixel.

```cpp
enum class PixelFormat
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| Indexed | 65536 | Especifica que os dados do pixel contêm valores indexados de cor, o que significa que eles são um índice para cores na tabela de cores do sistema. |
| Gdi | 131072 | Especifica que os dados do pixel contêm cores GDI. |
| Alpha | 262144 | Especifica que os dados do pixel contêm valores alfa que não são pré-multiplicados. |
| PAlpha | 524288 | Especifica que os dados do pixel contêm valores alfa pré-multiplicados. |
| Extended | 1048576 | Reservado. |
| Canonical | 2097152 | Especifica o formato de pixel de 32 bits por pixel com profundidade de cor de 24 bits e um canal alfa de 8 bits. |
| Undefined | 0 | Especifica que o formato de pixel está indefinido. |
| DontCare | 0 | O formato de pixel não está especificado. |
| Format1bppIndexed | n/a | Especifica que o formato de pixel é cor indexada de 1 bit por pixel. |
| Format4bppIndexed | n/a | Especifica que o formato de pixel é cor indexada de 4 bits por pixel. |
| Format8bppIndexed | n/a | Especifica que o formato de pixel é cor indexada de 8 bits por pixel. |
| Format16bppGrayScale | n/a | Especifica que o formato de pixel tem 16 bits por pixel. As informações de cor especificam 65536 tons de cinza. |
| Format16bppRgb555 | n/a | Especifica que o formato de pixel tem 16 bits por pixel com 5 bits para cada um dos componentes vermelho, verde e azul, e o bit restante não é usado. |
| Format16bppRgb565 | n/a | Especifica que o formato de pixel tem 16 bits por pixel com 5 bits para o vermelho, 6 bits para o verde e 5 bits para o azul. |
| Format16bppArgb1555 | n/a | Especifica que o formato de pixel tem 16 bits por pixel com 5 bits para cada um dos componentes vermelho, verde e azul e 1 bit para alfa. |
| Format24bppRgb | n/a | Especifica que o formato de pixel tem 24 bits por pixel com 8 bits para cada um dos componentes vermelho, verde e azul. |
| Format32bppRgb | n/a | Especifica que o formato de pixel tem 32 bits por pixel com 8 bits para cada um dos componentes vermelho, verde e azul e os 8 bits restantes não são usados. |
| Format32bppArgb | n/a | Especifica que o formato de pixel tem 32 bits por pixel com 8 bits para cada um dos componentes vermelho, verde e azul e 8 bits para alfa. |
| Format32bppPArgb | n/a | Especifica que o formato de pixel tem 32 bits por pixel com 8 bits para cada um dos componentes vermelho, verde e azul e 8 bits para alfa. Os componentes vermelho, verde e azul são pré-multiplicados de acordo com o valor do componente alfa. |
| Format48bppRgb | n/a | Especifica que o formato de pixel tem 48 bits por pixel com 16 bits para cada um dos componentes vermelho, verde e azul. |
| Format64bppArgb | n/a | Especifica que o formato de pixel tem 64 bits por pixel com 16 bits para cada um dos componentes vermelho, verde e azul e 16 bits para alfa. |
| Format64bppPArgb | n/a | Especifica que o formato de pixel tem 64 bits por pixel com 16 bits para cada um dos componentes vermelho, verde e azul e 16 bits para alfa. Os componentes vermelho, verde e azul são pré-multiplicados de acordo com o valor do componente alfa. |
| Format32bppCMYK | n/a | Especifica que o formato de pixel tem 32 bits por pixel com 8 bits para cada um dos componentes ciano, magenta, amarelo e preto. |
| Max | 16 | O valor máximo deste enum. |

## Veja Também

* Namespace [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)