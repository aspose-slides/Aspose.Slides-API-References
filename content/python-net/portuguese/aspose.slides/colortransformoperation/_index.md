---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/colortransformoperation/
---
## Enumeração ColorTransformOperation

Define a operação de transformação de cor.

O tipo ColorTransformOperation expõe os seguintes membros:

## Campos

| Campo | Descrição |
| :- | :- |
| TINT | Aplica um tom à cor. O parâmetro está no intervalo entre 0 (cor original) e 1 (branco). |
| SHADE | Escurece a cor. O parâmetro está no intervalo entre 0 (cor original) e 1 (preto). |
| COMPLEMENT | Altera a cor para uma complementar RGB.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Altera a cor para uma cor invertida.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Altera a cor para um tom de cinza com a mesma luminosidade. Parâmetro ignorado. |
| SET_ALPHA | Define um componente alfa da cor. O parâmetro está no intervalo entre 0 (transparente) e 1 (opaco). |
| ADD_ALPHA | Adiciona o valor do parâmetro a um componente alfa da cor. O parâmetro está no intervalo entre -1 e 1. |
| MULTIPLY_ALPHA | Multiplica um componente alfa por um valor de parâmetro. |
| SET_HUE | Altera o componente matiz da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 360. |
| ADD_HUE | Adiciona o valor do parâmetro ao componente matiz da cor. O parâmetro está no intervalo entre -360 e 360. |
| MULTIPLY_HUE | Multiplica o componente matiz por um valor de parâmetro. |
| SET_SATURATION | Altera o componente saturação da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| ADD_SATURATION | Adiciona o valor do parâmetro ao componente saturação da cor. O parâmetro está no intervalo entre -1 e 1. |
| MULTIPLY_SATURATION | Multiplica o componente saturação por um valor de parâmetro. |
| SET_LUMINANCE | Altera o componente luminância da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| ADD_LUMINANCE | Adiciona o valor do parâmetro ao componente luminância da cor. O parâmetro está no intervalo entre -1 e 1. |
| MULTIPLY_LUMINANCE | Multiplica o componente luminância por um valor de parâmetro. |
| SET_RED | Altera o componente vermelho da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| ADD_RED | Adiciona o valor do parâmetro ao componente vermelho da cor. O parâmetro está no intervalo entre -1 e 1. |
| MULTIPLY_RED | Multiplica o componente vermelho por um parâmetro. |
| SET_GREEN | Altera o componente verde da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 1. |
| ADD_GREEN | Adiciona um parâmetro ao componente verde da cor. O parâmetro está no intervalo entre -1 e 1. |
| MULTIPLY_GREEN | Multiplica o componente verde por um valor de parâmetro. |
| SET_BLUE | Altera o componente azul da cor para o valor do parâmetro. O parâmetro está no intervalo entre 0 e 360. |
| ADD_BLUE | Adiciona o valor do parâmetro ao componente azul da cor. O parâmetro está no intervalo entre -1 e 1. |
| MULTIPLY_BLUE | Multiplica o componente azul por um valor de parâmetro. |
| GAMMA | Correção gama. Parâmetro ignorado. |
| INVERSE_GAMMA | Correção gama inversa. Parâmetro ignorado. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)