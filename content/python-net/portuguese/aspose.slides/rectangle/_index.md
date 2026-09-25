---
title: Rectangle class
second_title: Aspose.Slides para Python via .NET Referência de API
description: Armazena um conjunto de quatro inteiros que representam a localização e o tamanho de um retângulo.
type: docs
url: /pt/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle classe

Armazena um conjunto de quatro inteiros que representam a localização e o tamanho de um retângulo. Compatível com .NET `System.Drawing.Rectangle`.

O tipo Rectangle expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/pt/aspose.slides/rectangle/__init__/#int-int-int-int) | Cria um retângulo com a localização e tamanho especificados. Valores de ponto flutuante são truncados para inteiros. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`x`](/slides/python-net/pt/aspose.slides/rectangle/x/) | Obtém a coordenada x do canto superior esquerdo deste retângulo.<br/>            Somente leitura **int**. |
| [`y`](/slides/python-net/pt/aspose.slides/rectangle/y/) | Obtém a coordenada y do canto superior esquerdo deste retângulo.<br/>            Somente leitura **int**. |
| [`width`](/slides/python-net/pt/aspose.slides/rectangle/width/) | Obtém a largura deste retângulo.<br/>            Somente leitura **int**. |
| [`height`](/slides/python-net/pt/aspose.slides/rectangle/height/) | Obtém a altura deste retângulo.<br/>            Somente leitura **int**. |
| [`left`](/slides/python-net/pt/aspose.slides/rectangle/left/) | Obtém a coordenada x da borda esquerda deste retângulo. Igual a `x`.<br/>            Somente leitura **int**. |
| [`top`](/slides/python-net/pt/aspose.slides/rectangle/top/) | Obtém a coordenada y da borda superior deste retângulo. Igual a `y`.<br/>            Somente leitura **int**. |
| [`right`](/slides/python-net/pt/aspose.slides/rectangle/right/) | Obtém a coordenada x que é a soma de `x` e `width` deste retângulo.<br/>            Somente leitura **int**. |
| [`bottom`](/slides/python-net/pt/aspose.slides/rectangle/bottom/) | Obtém a coordenada y que é a soma de `y` e `height` deste retângulo.<br/>            Somente leitura **int**. |
| [`is_empty`](/slides/python-net/pt/aspose.slides/rectangle/is_empty/) | Especifica se todas as propriedades numéricas deste retângulo têm valores zero.<br/>            Somente leitura **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/pt/aspose.slides/rectangle/contains/#int-int) | Determina se o ponto especificado está contido dentro deste retângulo. |
| [`contains(self, point)`](/slides/python-net/pt/aspose.slides/rectangle/contains/#point) | Determina se o ponto especificado está contido dentro deste retângulo. |
| [`contains(self, rect)`](/slides/python-net/pt/aspose.slides/rectangle/contains/#rectangle) | Determina se a região retangular representada por `rect` está totalmente contida dentro deste retângulo. |


### Observações

Retângulos são comparados pela sua localização e tamanho com `==` e podem ser usados como chaves de dicionário ou membros de conjunto.


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)