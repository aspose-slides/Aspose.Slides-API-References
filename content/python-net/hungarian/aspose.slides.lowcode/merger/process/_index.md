---
title: process method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Több, azonos formátumú PowerPoint bemutatót egyetlen bemutatófájlba egyesít.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| input_file_names | **List[str]** | A bemeneti bemutató fájlneveket tartalmazó tömb. |
| output_file_name | **str** | Az eredményül kapott egyesített bemutatófájl kimeneti fájlneve. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobódik, ha a bemeneti fájlnevek érvénytelenek vagy a formátumok nem egyeznek. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Több, azonos formátumú PowerPoint bemutatót egyetlen bemutatófájlba egyesít.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| input_file_names | **List[str]** | A bemeneti bemutató fájlneveket tartalmazó tömb. |
| output_stream | **io.RawIOBase** | A kimeneti adatfolyam. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobódik, ha a bemeneti fájlnevek érvénytelenek vagy a formátumok nem egyeznek. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Több, azonos formátumú PowerPoint bemutatót egyetlen bemutatófájlba egyesít.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| input_file_names | **List[str]** | A bemeneti bemutató fájlneveket tartalmazó tömb. |
| output_file_name | **str** | Az eredményül kapott egyesített bemutatófájl kimeneti fájlneve. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | A további beállítások, amelyek meghatározzák, hogyan kerül mentésre az egyesített bemutató. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobódik, ha a bemeneti fájlnevek érvénytelenek vagy a formátumok nem egyeznek. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Több, azonos formátumú PowerPoint bemutatót egyetlen bemutatófájlba egyesít.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| input_file_names | **List[str]** | A bemeneti bemutató fájlneveket tartalmazó tömb. |
| output_stream | **io.RawIOBase** | A kimeneti adatfolyam. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | A további beállítások, amelyek meghatározzák, hogyan kerül mentésre az egyesített bemutató. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor dobódik, ha a bemeneti fájlnevek érvénytelenek vagy a formátumok nem egyeznek. |



### Lásd még
* osztály [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions)
* osztály [`Merger`](/slides/python-net/hu/aspose.slides.lowcode/merger)
* modul [`aspose.slides.lowcode`](/slides/python-net/hu/aspose.slides.lowcode)
* könyvtár [`Aspose.Slides`](/slides/python-net)