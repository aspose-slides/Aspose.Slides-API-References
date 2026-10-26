---
title: StringChartValue class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/stringchartvalue/
---
## StringChartValue classe

Representa valor de string que pode ser armazenado em documento de apresentação pptx de duas maneiras:
1) em célula/células da pasta de trabalho relacionada ao gráfico;
2) como valor literal.

**Herança:**[`StringChartValue`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/pt/aspose.slides.charts/basechartvalue)

O tipo StringChartValue expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`data_source_type`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue/data_source_type/) | Especifica se a propriedade AsCell, AsCells, AsLiteralString ou AsLiteralDouble <br/> está presente nos descendentes. Em outras palavras, especifica o tipo <br/> do valor da propriedade Data.<br/> **Leitura/Gravação** [`DataSourceType`](/slides/python-net/pt/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue/data/) | Retorna ou define o objeto Data.<br/> **Leitura/Gravação** **any**. |
| [`as_cells`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue/as_cells/) | A atribuição de valor nulo não é permitida.<br/> O valor retornado nunca é None.<br/> **Leitura/Gravação** [`IChartCellCollection`](/slides/python-net/pt/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue/as_literal_string/) | Retorna ou define o valor como string literal.<br/> **Leitura/Gravação** **str**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Define o valor a partir da célula especificada. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Se a propriedade DataSourceType for DataSourceType.Worksheet, então este método retorna o endereço<br/> das células na pasta de trabalho que representam os dados de string. Caso contrário, retorna<br/> uma string vazia. |

### Veja Também
* classe [`BaseChartValue`](/slides/python-net/pt/aspose.slides.charts/basechartvalue)
* classe [`StringChartValue`](/slides/python-net/pt/aspose.slides.charts/stringchartvalue)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)