---
title: IStringChartValue class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue classe

Representa um valor de string que pode ser armazenado em um documento de apresentação pptx de duas maneiras:
            1) em célula(s) da pasta de trabalho relacionada ao gráfico;
            2) como valor literal.

O tipo IStringChartValue expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`as_literal_string`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/as_literal_string/) | Retorna ou define a string literal se a propriedade DataSourceType for DataSourceType.StringLiterals.<br/>            Leitura/gravação **str**. |
| [`as_cells`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/data/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`to_string(self)`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/to_string/#) | Retorna a representação da string. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Define o valor a partir da célula especificada. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/pt/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Se a propriedade DataSourceType for DataSourceType.Worksheet então este método retorna o endereço<br/>            das células na pasta de trabalho que representam os dados de string. Caso contrário, retorna<br/>            string vazia. |


### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)