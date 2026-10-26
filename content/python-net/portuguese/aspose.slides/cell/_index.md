---
title: Cell class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/cell/
---
## classe Cell

Representa uma célula de uma tabela.

O tipo Cell expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`offset_x`](/slides/python-net/pt/aspose.slides/cell/offset_x/) | Retorna a distância do lado esquerdo de uma tabela ao lado esquerdo de uma célula.<br/>            Somente leitura **float**. |
| [`offset_y`](/slides/python-net/pt/aspose.slides/cell/offset_y/) | Retorna a distância do lado superior de uma tabela ao lado superior de uma célula.<br/>            Somente leitura **float**. |
| [`first_row_index`](/slides/python-net/pt/aspose.slides/cell/first_row_index/) | Retorna o índice da primeira linha coberta pela célula.<br/>            Somente leitura **int**. |
| [`first_column_index`](/slides/python-net/pt/aspose.slides/cell/first_column_index/) | Retorna o índice da primeira coluna coberta pela célula.<br/>            Somente leitura **int**. |
| [`width`](/slides/python-net/pt/aspose.slides/cell/width/) | Retorna a largura da célula.<br/>            Somente leitura **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/cell/height/) | Retorna a altura da célula.<br/>            Somente leitura **float**. |
| [`minimal_height`](/slides/python-net/pt/aspose.slides/cell/minimal_height/) | Retorna a altura mínima de uma célula.<br/>            Esta é a soma das alturas mínimas de todas as linhas cobertas pela célula.<br/>            Somente leitura **float**. |
| [`margin_left`](/slides/python-net/pt/aspose.slides/cell/margin_left/) | Retorna ou define a margem esquerda em um TextFrame.<br/>            Leitura/Gravação **float**. |
| [`margin_right`](/slides/python-net/pt/aspose.slides/cell/margin_right/) | Retorna ou define a margem direita em um TextFrame.<br/>            Leitura/Gravação **float**. |
| [`margin_top`](/slides/python-net/pt/aspose.slides/cell/margin_top/) | Retorna ou define a margem superior em um TextFrame.<br/>            Leitura/Gravação **float**. |
| [`margin_bottom`](/slides/python-net/pt/aspose.slides/cell/margin_bottom/) | Retorna ou define a margem inferior em um TextFrame.<br/>            Leitura/Gravação **float**. |
| [`text_vertical_type`](/slides/python-net/pt/aspose.slides/cell/text_vertical_type/) | Retorna ou define o tipo de texto vertical.<br/>            Leitura/Gravação [`TextVerticalType`](/slides/python-net/pt/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/pt/aspose.slides/cell/text_anchor_type/) | Retorna ou define o tipo de âncora do texto.<br/>            Leitura/Gravação [`TextAnchorType`](/slides/python-net/pt/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/pt/aspose.slides/cell/anchor_center/) | Determina se a caixa de texto está centralizada dentro de uma célula.<br/>            Leitura/Gravação **bool**. |
| [`first_row`](/slides/python-net/pt/aspose.slides/cell/first_row/) | Obtém a primeira linha da célula.<br/>            Somente leitura [`IRow`](/slides/python-net/pt/aspose.slides/irow). |
| [`first_column`](/slides/python-net/pt/aspose.slides/cell/first_column/) | Obtém a primeira coluna da célula.<br/>            Somente leitura [`IColumn`](/slides/python-net/pt/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/pt/aspose.slides/cell/col_span/) | Retorna o número de colunas da grade da tabela pai que deverão ser abrangidas pela célula atual.<br/>            Esta propriedade permite que as células tenham a aparência de mescladas, pois abrangem os limites verticais de outras células na tabela.<br/>            Somente leitura **int**. |
| [`row_span`](/slides/python-net/pt/aspose.slides/cell/row_span/) | Retorna o número de linhas que uma célula mesclada abrange. Isso é usado em combinação com o atributo vMerge em outras células para especificar a célula inicial de uma mesclagem horizontal.<br/>            Somente leitura **int**. |
| [`text_frame`](/slides/python-net/pt/aspose.slides/cell/text_frame/) | Retorna o frame de texto de uma célula.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`table`](/slides/python-net/pt/aspose.slides/cell/table/) | Retorna o objeto Table pai de uma célula.<br/>            Somente leitura [`ITable`](/slides/python-net/pt/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/pt/aspose.slides/cell/is_merged_cell/) | Retorna verdadeiro se a célula está mesclada com alguma célula ajustada, falso caso contrário.<br/>            Somente leitura **bool**. |
| [`cell_format`](/slides/python-net/pt/aspose.slides/cell/cell_format/) | Retorna o objeto CellFormat que contém propriedades de formatação para esta célula.<br/>            Somente leitura [`ICellFormat`](/slides/python-net/pt/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/pt/aspose.slides/cell/slide/) | Retorna o slide pai de uma célula.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/cell/presentation/) | Retorna a apresentação pai de uma célula.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/pt/aspose.slides/cell/split_by_col_span/#int) | Divide a célula em duas células pelo índice da coluna. |
| [`split_by_row_span(self, index)`](/slides/python-net/pt/aspose.slides/cell/split_by_row_span/#int) | Divide a célula em duas células pelo índice da linha. |
| [`split_by_height(self, height)`](/slides/python-net/pt/aspose.slides/cell/split_by_height/#float) | Divide a célula pela altura. |
| [`split_by_width(self, width)`](/slides/python-net/pt/aspose.slides/cell/split_by_width/#float) | Divide a célula pela largura. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)