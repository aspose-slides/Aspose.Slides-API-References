---
title: add_table_from_workbook method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Načte tabulku ze zadaného sešitu Excel a přidá ji na konec dané kolekce tvarů na určených souřadnicích.

### Vrácená hodnota

Tabulka, která byla přidána do kolekce tvarů.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude tabulka přidána. |
| x | **float** | Souřadnice X pro umístění tabulky. |
| y | **float** | Souřadnice Y pro umístění tabulky. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/iexceldataworkbook) | Sešit Excel. |
| worksheet_name | **str** | Název listu, který tabulku obsahuje. |
| cell_range | **str** | Rozsah buněk definující tabulku (například "A1:D10"). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, když je některý z povinných parametrů None nebo prázdný, nebo když je zadaný list nebo rozsah buněk neplatný. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když je vstupní data ve formátu, který není podporován. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Načte tabulku ze souboru sešitu Excel a přidá ji na konec dané kolekce tvarů na určených souřadnicích.

### Vrácená hodnota

Tabulka, která byla přidána do kolekce tvarů.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude tabulka přidána. |
| x | **float** | Souřadnice X pro umístění tabulky. |
| y | **float** | Souřadnice Y pro umístění tabulky. |
| workbook_path | **str** | Cesta k souboru sešitu Excel. |
| worksheet_name | **str** | Název listu, který tabulku obsahuje. |
| cell_range | **str** | Rozsah buněk definující tabulku (například "A1:D10"). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, když je některý z povinných parametrů None nebo prázdný, nebo když je zadaný list nebo rozsah buněk neplatný. |
| **RuntimeError(Proxy error(IOException))** | Vyvoláno, když dojde k chybě I/O při přístupu k souboru sešitu. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když je vstupní data ve formátu, který není podporován. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Načte tabulku ze souboru sešitu Excel a přidá ji na konec dané kolekce tvarů na určených souřadnicích.

### Vrácená hodnota

Tabulka, která byla přidána do kolekce tvarů.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection) | Kolekce tvarů, do které bude tabulka přidána. |
| x | **float** | Souřadnice X pro umístění tabulky. |
| y | **float** | Souřadnice Y pro umístění tabulky. |
| workbook_stream | **io.RawIOBase** | Proud obsahující data sešitu. |
| worksheet_name | **str** | Název listu, který tabulku obsahuje. |
| cell_range | **str** | Rozsah buněk definující tabulku (například "A1:D10"). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, když je některý z povinných parametrů None nebo prázdný, nebo když je zadaný list nebo rozsah buněk neplatný. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když je vstupní data ve formátu, který není podporován. |



### Viz také
* třída [`ExcelWorkbookImporter`](/slides/python-net/cs/aspose.slides.importing/excelworkbookimporter)
* třída [`IExcelDataWorkbook`](/slides/python-net/cs/aspose.slides.excel/iexceldataworkbook)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* třída [`ITable`](/slides/python-net/cs/aspose.slides/itable)
* modul [`aspose.slides.importing`](/slides/python-net/cs/aspose.slides.importing)
* knihovna [`Aspose.Slides`](/slides/python-net)