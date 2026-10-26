---
title: add_chart_from_workbook method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

O gráfico que foi adicionado à coleção de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/pt/aspose.slides.excel/iexceldataworkbook) | A pasta de trabalho Excel. |
| worksheet_name | **str** | O nome da planilha que contém o gráfico. |
| chart_index | **int** | O índice baseado em zero da forma de gráfico a ser inserida. <br/><br/>            Este índice pode ser obtido usando o método **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Se `true`, a pasta de trabalho inteira será incorporada ao gráfico; <br/><br/>            se `false`, somente os dados do gráfico serão incorporados. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None, está vazio ou se o gráfico não puder ser encontrado na pasta de trabalho. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

O gráfico que foi adicionado à coleção de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/pt/aspose.slides.excel/iexceldataworkbook) | A pasta de trabalho Excel. |
| worksheet_name | **str** | O nome da planilha que contém o gráfico. |
| chart_name | **str** | O nome do gráfico a ser adicionado. |
| embed_all_workbook | **bool** | Se `true`, a pasta de trabalho inteira será incorporada ao gráfico; <br/><br/>            se `false`, somente os dados do gráfico serão incorporados. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None, está vazio ou se o gráfico não puder ser encontrado na pasta de trabalho. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

O gráfico que foi adicionado à coleção de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbook_stream | **io.RawIOBase** | Um fluxo contendo os dados da pasta de trabalho. |
| worksheet_name | **str** | O nome da planilha que contém o gráfico. |
| chart_name | **str** | O nome do gráfico a ser adicionado. |
| embed_all_workbook | **bool** | Se `true`, a pasta de trabalho inteira será incorporada ao gráfico; <br/><br/>            se `false`, somente os dados do gráfico serão incorporados. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None, está vazio ou se o gráfico não puder ser encontrado na pasta de trabalho. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançado quando os dados de entrada estão em um formato não suportado. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Recupera um gráfico da pasta de trabalho Excel especificada e o adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

O gráfico que foi adicionado à coleção de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual o gráfico será adicionado. |
| x | **float** | A coordenada X para posicionar o gráfico. |
| y | **float** | A coordenada Y para posicionar o gráfico. |
| workbook_path | **str** | O caminho do arquivo para a pasta de trabalho que contém o gráfico. |
| worksheet_name | **str** | O nome da planilha que contém o gráfico. |
| chart_name | **str** | O nome do gráfico a ser adicionado. |
| embed_workbook | **bool** | Se `true`, a pasta de trabalho será incorporada ao gráfico; <br/><br/>            se `false`, o gráfico será vinculado à pasta de trabalho externa. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None, está vazio ou se o gráfico não puder ser encontrado na pasta de trabalho. |
| **RuntimeError(Proxy error(IOException))** | Lançado quando ocorre um erro de E/S ao acessar o arquivo. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançado quando os dados de entrada estão em um formato não suportado. |



### Veja também
* classe [`ExcelWorkbookImporter`](/slides/python-net/pt/aspose.slides.importing/excelworkbookimporter)
* classe [`IExcelDataWorkbook`](/slides/python-net/pt/aspose.slides.excel/iexceldataworkbook)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides.importing`](/slides/python-net/pt/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)