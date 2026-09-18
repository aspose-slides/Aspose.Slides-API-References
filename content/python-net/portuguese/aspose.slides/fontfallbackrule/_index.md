---
title: FontFallBackRule class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/fontfallbackrule/
---
## FontFallBackRule classe

Representa a regra de substituição de fonte

O tipo FontFallBackRule expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Cria uma nova instância. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Cria uma nova instância. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`range_start_index`](/slides/python-net/pt/aspose.slides/fontfallbackrule/range_start_index/) | Obtém o primeiro índice do intervalo unicode contínuo. |
| [`range_end_index`](/slides/python-net/pt/aspose.slides/fontfallbackrule/range_end_index/) | Obtém o último índice do intervalo unicode contínuo. |
| [`count`](/slides/python-net/pt/aspose.slides/fontfallbackrule/count/) | Obtém o número de fontes realmente definidas para o intervalo.<br/>            Somente leitura **int**. |

Obtém o nome da fonte no índice especificado.
            Somente leitura [`IFontFallBackRule`](/slides/python-net/pt/aspose.slides/ifontfallbackrule).

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Adiciona nova(s) fonte(s) à lista de fontes FallBack. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Adiciona novas fontes à lista de fontes FallBack. |
| [`to_array(self)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/to_array/#) | Cria e devolve um array com todas as fontes FallBack para esta regra. |
| [`to_array(self, start_index, count)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/to_array/#int-int) | Cria e devolve um array com todas as fontes FallBack do intervalo especificado na lista. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/clear/#) | Remove todas as fontes da lista. |
| [`remove(self, font_name)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/remove/#str) | Remove a primeira ocorrência de uma fonte FallBack específica da lista. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/remove_at/#int) | Remove a fonte FallBack no índice especificado da lista. |
| [`index_of(self, font_name)`](/slides/python-net/pt/aspose.slides/fontfallbackrule/index_of/#str) | Retorna o índice da regra especificada na coleção. |


### Veja Também
* classe [`IFontFallBackRule`](/slides/python-net/pt/aspose.slides/ifontfallbackrule)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)