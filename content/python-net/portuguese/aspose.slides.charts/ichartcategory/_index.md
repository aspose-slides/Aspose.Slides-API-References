---
title: IChartCategory class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/ichartcategory/
---
## IChartCategory classe

Representa categorias de gráfico.

O tipo IChartCategory expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`use_cell`](/slides/python-net/pt/aspose.slides.charts/ichartcategory/use_cell/) | Se verdadeiro, a propriedade AsCell está em vigor. Em outras palavras, a planilha é usada para <br/>            armazenar a categoria (este caso suporta uma categoria de vários níveis).<br/>            Se falso, a propriedade AsLiteral está em vigor. Em outras palavras, a planilha NÃO é usada <br/>            para armazenar a categoria (e este caso não oferece suporte a categorias de vários níveis).<br/>            Somente leitura **bool**. |
| [`as_cell`](/slides/python-net/pt/aspose.slides.charts/ichartcategory/as_cell/) | Retorna ou define o objeto IChartDataCell.<br/>            Se a categoria for de vários níveis, então é usado o objeto IChartDataCell para o nível "0".<br/>            Leitura/gravação [`IChartDataCell`](/slides/python-net/pt/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/pt/aspose.slides.charts/ichartcategory/as_literal/) | Retorna ou define AsLiteral se UseCell for falso.<br/>            Leitura/gravação **any**. |
| [`value`](/slides/python-net/pt/aspose.slides.charts/ichartcategory/value/) | Se UseCell for verdadeiro, então esta propriedade representa a propriedade AsCell.Value.<br/>            Se UseCell for falso, então esta propriedade representa a propriedade AsLiteral.<br/>            Leitura/gravação **any**. |
| [`grouping_levels`](/slides/python-net/pt/aspose.slides.charts/ichartcategory/grouping_levels/) | Contêiner gerenciado dos valores dos níveis de agrupamento da categoria de gráfico.<br/>            Categoria de vários níveis contém mais de um nível de agrupamento.<br/>            A indexação dos níveis de agrupamento começa em zero.<br/>            Somente leitura [`IChartCategoryLevelsManager`](/slides/python-net/pt/aspose.slides.charts/ichartcategorylevelsmanager). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`remove(self)`](/slides/python-net/pt/aspose.slides.charts/ichartcategory/remove/#) | Remove a categoria do gráfico. |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)