---
title: RectangleF class
second_title: Aspose.Slides para Python via Referência da API .NET
description: Armazena um conjunto de quatro números de ponto flutuante que representam a localização e o tamanho de um retângulo.
type: docs
url: /pt/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF classe

Armazena um conjunto de quatro números de ponto flutuante que representam a localização e o tamanho de um retângulo. Compatível com .NET `System.Drawing.RectangleF`.

**Herança:**[`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/pt/aspose.slides/rectangle)

O tipo RectangleF expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/pt/aspose.slides/rectanglef/__init__/#float-float-float-float) | Cria um retângulo com a localização e tamanho especificados. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`x`](/slides/python-net/pt/aspose.slides/rectanglef/x/) | Obtém a coordenada x do canto superior esquerdo deste retângulo.<br/>            Somente leitura **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/rectanglef/y/) | Obtém a coordenada y do canto superior esquerdo deste retângulo.<br/>            Somente leitura **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/rectanglef/width/) | Obtém a largura deste retângulo.<br/>            Somente leitura **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/rectanglef/height/) | Obtém a altura deste retângulo.<br/>            Somente leitura **float**. |
| [`left`](/slides/python-net/pt/aspose.slides/rectanglef/left/) | Obtém a coordenada x da borda esquerda deste retângulo. Igual a `x`.<br/>            Somente leitura **float**. |
| [`top`](/slides/python-net/pt/aspose.slides/rectanglef/top/) | Obtém a coordenada y da borda superior deste retângulo. Igual a `y`.<br/>            Somente leitura **float**. |
| [`right`](/slides/python-net/pt/aspose.slides/rectanglef/right/) | Obtém a coordenada x que é a soma de `x` e `width` deste retângulo.<br/>            Somente leitura **float**. |
| [`bottom`](/slides/python-net/pt/aspose.slides/rectanglef/bottom/) | Obtém a coordenada y que é a soma de `y` e `height` deste retângulo.<br/>            Somente leitura **float**. |
| [`is_empty`](/slides/python-net/pt/aspose.slides/rectanglef/is_empty/) | Especifica se todas as propriedades numéricas deste retângulo têm valores zero.<br/>            Somente leitura **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/pt/aspose.slides/rectanglef/contains/#float-float) | Determina se o ponto especificado está contido dentro deste retângulo. |
| [`contains(self, point)`](/slides/python-net/pt/aspose.slides/rectanglef/contains/#pointf) | Determina se o ponto especificado está contido dentro deste retângulo. |
| [`contains(self, rect)`](/slides/python-net/pt/aspose.slides/rectanglef/contains/#rectanglef) | Determina se a região retangular representada por `rect` está completamente contida dentro deste retângulo. |


### Observações

Retângulos são comparados por sua localização e tamanho com `==` e podem ser usados como chaves de dicionário ou membros de conjunto.


### Ver também
* classe [`Rectangle`](/slides/python-net/pt/aspose.slides/rectangle)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)