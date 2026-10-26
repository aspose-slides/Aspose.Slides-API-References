---
title: ColorTransformOperation
second_title: Aspose.Slides para C++ Referência da API
description: Define a operação de transformação de cor.
type: docs
weight: 5747
url: /pt/aspose.slides/colortransformoperation/
---
## Enum ColorTransformOperation

Define a operação de transformação de cor.

```cpp
enum class ColorTransformOperation
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Tint | 0 | Aplica um tom à cor. O parâmetro está no intervalo entre 0 (cor original) e 1 (branco). |
| Shade | 1 | Aplica sombra à cor. O parâmetro está no intervalo entre 0 (cor original) e 1 (preto). |
| Complement | 2 | Altera a cor para uma complementar em RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Altera a cor para uma cor invertida. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Altera a cor para um tom de cinza com a mesma luminosidade. Parâmetro ignorado. |
| SetAlpha | 5 | Define um componente alfa da cor. O parâmetro está no intervalo entre 0 (transparente) e 1 (opaco). |
| AddAlpha | 6 | Adiciona o valor do parâmetro a um componente alfa da cor. O parâmetro está no intervalo entre -1 e 1. |
| MultiplyAlpha | 7 | Multiplica um componente alfa pelo valor do parâmetro. |
| SetHue | 8 | Altera o componente de matiz da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 360. |
| AddHue | 9 | Adiciona o valor do parâmetro ao componente de matiz da cor. O parâmetro está no intervalo entre -360 e 360. |
| MultiplyHue | 10 | Multiplica o componente de matiz pelo valor do parâmetro. |
| SetSaturation | 11 | Altera o componente de saturação da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| AddSaturation | 12 | Adiciona o valor do parâmetro ao componente de saturação da cor. O parâmetro está no intervalo entre -1 e 1. |
| MultiplySaturation | 13 | Multiplica o componente de saturação pelo valor do parâmetro. |
| SetLuminance | 14 | Altera o componente de luminância da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| AddLuminance | 15 | Adiciona o valor do parâmetro ao componente de luminância da cor. O parâmetro está no intervalo entre -1 e 1. |
| MultiplyLuminance | 16 | Multiplica o componente de luminância pelo valor do parâmetro. |
| SetRed | 17 | Altera o componente vermelho da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| AddRed | 18 | Adiciona o valor do parâmetro ao componente vermelho da cor. O parâmetro está no intervalo entre -1 e 1. |
| MultiplyRed | 19 | Multiplica um componente vermelho por um parâmetro. |
| SetGreen | 20 | Altera o componente verde da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| AddGreen | 21 | Adiciona um parâmetro ao componente verde da cor. O parâmetro está no intervalo entre -1 e 1. |
| MultiplyGreen | 22 | Multiplica um componente verde pelo valor do parâmetro. |
| SetBlue | 23 | Altera o componente azul da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 360. |
| AddBlue | 24 | Adiciona o valor do parâmetro ao componente azul da cor. O parâmetro está no intervalo entre -1 e 1. |
| MultiplyBlue | 25 | Multiplica um componente azul pelo valor do parâmetro. |
| Gamma | 26 | Correção gama. Parâmetro ignorado. |
| InverseGamma | 27 | Correção gama inversa. Parâmetro ignorado. |

## Veja Também

* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)