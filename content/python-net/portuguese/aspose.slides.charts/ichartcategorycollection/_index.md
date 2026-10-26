---
title: IChartCategoryCollection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection classe

Representa a coleção de [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory)

O tipo IChartCategoryCollection expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`use_cells`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/use_cells/) | Se true então a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis).<br/>            Se false então a planilha NÃO é usada para armazenar valores (e este caso não suporta uma <br/>            categorias de múltiplos níveis).<br/>            Leitura/gravação **bool**. |
| [`grouping_level_count`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Retorna a contagem de níveis de agrupamento de categorias usados.<br/>            É maior que um para categorias de múltiplos níveis.<br/>            Somente leitura **int**. |

Obtém o elemento no índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Se a categoria existir na coleção, retorne-a. Caso contrário, cria uma nova categoria de gráfico a partir de <br/>            [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell) e a adiciona à coleção. |
| [`add(self, value)`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/add/#any) | Cria um novo [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory) a partir do valor e o adiciona à coleção. |
| [`index_of(self, value)`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Procura o [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory) especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a coleção. |
| [`remove(self, value)`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Remove o valor especificado. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Remove o elemento no índice fornecido. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides.charts/ichartcategorycollection/clear/#) | Remove todos os elementos da coleção. |

### Veja Também
* classe [`IChartCategory`](/slides/python-net/pt/aspose.slides.charts/ichartcategory)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)