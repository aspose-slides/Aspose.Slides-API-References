---
title: add_table_from_workbook method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Recupera uma tabela da pasta de trabalho do Excel especificada e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

A tabela que foi adicionada à coleção de formas.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual a tabela será adicionada. |
| x | **float** | A coordenada X para posicionar a tabela. |
| y | **float** | A coordenada Y para posicionar a tabela. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/pt/aspose.slides.excel/iexceldataworkbook) | A pasta de trabalho do Excel. |
| worksheet_name | **str** | O nome da planilha que contém a tabela. |
| cell_range | **str** | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None ou vazio, ou quando a planilha ou intervalo de células especificados são inválidos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançado quando os dados de entrada estão em um formato não suportado. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Recupera uma tabela do arquivo de pasta de trabalho do Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

A tabela que foi adicionada à coleção de formas.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual a tabela será adicionada. |
| x | **float** | A coordenada X para posicionar a tabela. |
| y | **float** | A coordenada Y para posicionar a tabela. |
| workbook_path | **str** | O caminho para o arquivo da pasta de trabalho do Excel. |
| worksheet_name | **str** | O nome da planilha que contém a tabela. |
| cell_range | **str** | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None ou vazio, ou quando a planilha ou intervalo de células especificados são inválidos. |
| **RuntimeError(Proxy error(IOException))** | Lançado quando ocorre um erro de E/S ao acessar o arquivo da pasta de trabalho. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançado quando os dados de entrada estão em um formato não suportado. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Recupera uma tabela do arquivo de pasta de trabalho do Excel especificado e a adiciona ao final da coleção de formas fornecida nas coordenadas especificadas.

### Retorna

A tabela que foi adicionada à coleção de formas.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection) | A coleção de formas à qual a tabela será adicionada. |
| x | **float** | A coordenada X para posicionar a tabela. |
| y | **float** | A coordenada Y para posicionar a tabela. |
| workbook_stream | **io.RawIOBase** | Um fluxo contendo os dados da pasta de trabalho. |
| worksheet_name | **str** | O nome da planilha que contém a tabela. |
| cell_range | **str** | O intervalo de células que define a tabela (por exemplo, "A1:D10"). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando qualquer parâmetro obrigatório é None ou vazio, ou quando a planilha ou intervalo de células especificados são inválidos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lançado quando os dados de entrada estão em um formato não suportado. |



### Veja Também
* classe [`ExcelWorkbookImporter`](/slides/python-net/pt/aspose.slides.importing/excelworkbookimporter)
* classe [`IExcelDataWorkbook`](/slides/python-net/pt/aspose.slides.excel/iexceldataworkbook)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* classe [`ITable`](/slides/python-net/pt/aspose.slides/itable)
* módulo [`aspose.slides.importing`](/slides/python-net/pt/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)