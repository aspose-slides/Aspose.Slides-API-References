---
title: ExcelDataWorkbook class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook classe

Representa um workbook que fornece acesso a dados do Excel para uso geral.

O tipo ExcelDataWorkbook expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/__init__/#str) | Inicializa uma nova instância usando o caminho de arquivo especificado. |
| [`__init__(self, stream)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Inicializa uma nova instância da classe usando o fluxo fornecido. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Recupera uma célula da planilha especificada usando seu índice e coordenadas da célula. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Recupera uma célula da planilha especificada usando seu nome e coordenadas da célula. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (por exemplo, "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (por exemplo, "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Recupera uma coleção de células do livro de trabalho que correspondem à fórmula especificada. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de um livro de trabalho Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/pt/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Recupera os nomes de todas as planilhas contidas no livro de trabalho Excel. |


### Veja Também
* módulo [`aspose.slides.excel`](/slides/python-net/pt/aspose.slides.excel)
* biblioteca [`Aspose.Slides`](/slides/python-net)