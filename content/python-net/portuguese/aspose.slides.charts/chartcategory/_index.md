---
title: ChartCategory class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chartcategory/
---
## ChartCategory classe

Representa categorias de gráfico.

O tipo ChartCategory expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`use_cell`](/slides/python-net/pt/aspose.slides.charts/chartcategory/use_cell/) | Se true então a propriedade AsCell é efetiva. Em outras palavras, a planilha é usada para <br/>            armazenar a categoria (este caso suporta uma categoria de múltiplos níveis).<br/>            Se false então a propriedade AsLiteral é efetiva. Em outras palavras, a planilha NÃO é usada <br/>            para armazenar a categoria (e este caso não suporta categorias de múltiplos níveis).<br/>            Somente leitura **bool**. |
| [`as_cell`](/slides/python-net/pt/aspose.slides.charts/chartcategory/as_cell/) | Retorna ou define o objeto IChartDataCell.<br/>            Se a categoria for de múltiplos níveis então usa o objeto IChartDataCell para o nível \"0\".<br/>            Leitura/gravação [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/pt/aspose.slides.charts/chartcategory/as_literal/) | Retorna ou define o objeto AsLiteral.<br/>            Leitura/gravação **any**. |
| [`value`](/slides/python-net/pt/aspose.slides.charts/chartcategory/value/) | Se UseCell for true então esta propriedade representa a propriedade AsCell.Value.<br/>            Se UseCell for false então esta propriedade representa a propriedade AsLiteral.<br/>            Leitura/gravação **any**. |
| [`grouping_levels`](/slides/python-net/pt/aspose.slides.charts/chartcategory/grouping_levels/) | Contêiner gerenciado dos valores dos níveis de agrupamento da categoria de gráfico.<br/>            Categoria de múltiplos níveis contém mais de um nível de agrupamento.<br/>            A indexação dos níveis de agrupamento começa em zero.<br/>            Somente leitura [`IChartCategoryLevelsManager`](/slides/python-net/pt/aspose.slides.charts/ichartcategorylevelsmanager). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`remove(self)`](/slides/python-net/pt/aspose.slides.charts/chartcategory/remove/#) | Remove a categoria do gráfico. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)