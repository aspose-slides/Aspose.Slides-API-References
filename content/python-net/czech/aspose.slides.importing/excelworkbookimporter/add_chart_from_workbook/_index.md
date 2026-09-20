---
title: add_chart_from_workbook method
second_title: Aspose.Slides pro Python via .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Načte graf ze zadaného sešitu Excel a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/iexceldataworkbook) | Sešit Excel. |
| worksheet_name | **str** | Název listu, který obsahuje graf. |
| chart_index | **int** | Nulový index tvaru grafu, který se má vložit. <br/><br/>            Tento index lze získat pomocí metody **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Pokud je `true`, celý sešit bude vložen do grafu; <br/><br/>            pokud je `false`, budou vložena pouze data grafu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je libovolný povinný parametr `None`, prázdný, nebo pokud graf nelze v sešitu najít. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Načte graf ze zadaného sešitu Excel a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/iexceldataworkbook) | Sešit Excel. |
| worksheet_name | **str** | Název listu, který obsahuje graf. |
| chart_name | **str** | Název grafu, který má být přidán. |
| embed_all_workbook | **bool** | Pokud je `true`, celý sešit bude vložen do grafu; <br/><br/>            pokud je `false`, budou vložena pouze data grafu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je libovolný povinný parametr `None`, prázdný, nebo pokud graf nelze v sešitu najít. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Načte graf ze zadaného sešitu Excel a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbook_stream | **io.RawIOBase** | Proud obsahující data sešitu. |
| worksheet_name | **str** | Název listu, který obsahuje graf. |
| chart_name | **str** | Název grafu, který má být přidán. |
| embed_all_workbook | **bool** | Pokud je `true`, celý sešit bude vložen do grafu; <br/><br/>            pokud je `false`, budou vložena pouze data grafu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je libovolný povinný parametr `None`, prázdný, nebo pokud graf nelze v sešitu najít. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolána, když jsou vstupní data ve formátu, který není podporován. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Načte graf ze zadaného sešitu Excel a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbook_path | **str** | Cesta k souboru sešitu obsahujícímu graf. |
| worksheet_name | **str** | Název listu, který obsahuje graf. |
| chart_name | **str** | Název grafu, který má být přidán. |
| embed_workbook | **bool** | Pokud je `true`, sešit bude vložen do grafu; <br/><br/>            pokud je `false`, graf bude odkazovat na externí sešit. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je libovolný povinný parametr `None`, prázdný, nebo pokud graf nelze v sešitu najít. |
| **RuntimeError(Proxy error(IOException))** | Vyvolána, když dojde k chybě vstupu/výstupu při přístupu k souboru. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolána, když jsou vstupní data ve formátu, který není podporován. |



### Viz také
* třída [`ExcelWorkbookImporter`](/slides/python-net/cs/aspose.slides.importing/excelworkbookimporter)
* třída [`IExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/iexceldataworkbook)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides.importing`](/slides/python-net/cs/aspose.slides.importing)
* knihovna [`Aspose.Slides`](/slides/python-net)