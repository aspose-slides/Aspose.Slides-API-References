---
title: ChartCategory class
second_title: Aspose.Slides para Python via .NET API de Referência
description: 
type: docs
url: /pt/aspose.slides.charts/chartcategory/
---
## classe ChartCategory

Representa categorias de gráfico.

O tipo ChartCategory expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/pt/aspose.slides.charts/chartcategory/use_cell/) | Se verdadeiro, então a propriedade AsCell é efetiva. Em outras palavras, a planilha é usada para <br/>            armazenar a categoria (este caso suporta uma categoria de vários níveis).<br/>            Se falso, então a propriedade AsLiteral é efetiva. Em outras palavras, a planilha NÃO é usada <br/>            para armazenar a categoria (e este caso não suporta categorias de vários níveis).<br/>            Somente leitura **bool**. |
| [`as_cell`](/slides/python-net/pt/aspose.slides.charts/chartcategory/as_cell/) | Retorna ou define o objeto IChartDataCell.<br/>            Se a categoria for de vários níveis, então é usado o objeto IChartDataCell para o nível "0".<br/>            Leitura/escrita [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/pt/aspose.slides.charts/chartcategory/as_literal/) | Retorna ou define o objeto AsLiteral.<br/>            Leitura/escrita **any**. |
| [`value`](/slides/python-net/pt/aspose.slides.charts/chartcategory/value/) | Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value.<br/>            Se UseCell for false, então esta propriedade representa a propriedade AsLiteral.<br/>            Leitura/escrita **any**. |
| [`grouping_levels`](/slides/python-net/pt/aspose.slides.charts/chartcategory/grouping_levels/) | Contêiner gerenciado dos valores dos níveis de agrupamento da categoria de gráfico.<br/>            Categoria de vários níveis contém mais de um nível de agrupamento.<br/>            A indexação dos níveis de agrupamento começa em zero.<br/>            Somente leitura [`IChartCategoryLevelsManager`](/slides/python-net/pt/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/pt/aspose.slides.charts/chartcategory/cached_value/) | Obtém o valor em cache de uma categoria de gráfico.<br/>            Somente leitura [`ICachedChartValue`](/slides/python-net/pt/aspose.slides.charts/icachedchartvalue). |

## Métodos

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/pt/aspose.slides.charts/chartcategory/remove/#) | Remove a categoria do gráfico. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)