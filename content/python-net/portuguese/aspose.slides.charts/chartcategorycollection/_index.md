---
title: ChartCategoryCollection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection classe

Representa a coleção de [`ChartCategory`](/slides/python-net/pt/aspose.slides.charts/chartcategory)

O tipo ChartCategoryCollection expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`use_cells`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/use_cells/) | Se verdadeiro, a planilha é usada para armazenar categorias (este caso suporta categorias de vários níveis).<br/>            Se falso, a planilha NÃO é usada para armazenar valores (e este caso não suporta<br/>            categorias de vários níveis).<br/>            Leitura/gravação **bool**. |
| [`grouping_level_count`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Retorna a contagem dos níveis de agrupamento de categoria usados.<br/>            É maior que um para categorias de múltiplos níveis.<br/>            Somente leitura **int**. |

Obtém o elemento no índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Se a categoria existir na coleção, retorná-la. Caso contrário, cria uma nova categoria de gráfico a partir de <br/>            [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) e a adiciona à coleção. |
| [`add(self, value)`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/add/#any) | Cria um novo [`ChartCategory`](/slides/python-net/pt/aspose.slides.charts/chartcategory) a partir do valor e o adiciona à coleção. |
| [`index_of(self, value)`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Pesquisa o [`ChartCategory`](/slides/python-net/pt/aspose.slides.charts/chartcategory) especificado e retorna o índice baseado em zero da primeira ocorrência dentro da coleção inteira. |
| [`remove(self, value)`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Remove o valor especificado. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Remove o elemento no índice fornecido. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides.charts/chartcategorycollection/clear/#) | Remove todos os elementos da coleção. |


### Veja Também
* classe [`ChartCategory`](/slides/python-net/pt/aspose.slides.charts/chartcategory)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)