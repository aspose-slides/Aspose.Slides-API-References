---
title: to_jpeg method
second_title: Aspose.Slides a Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Átalakítja a bemeneti prezentációt JPEG formátumú képek halmazává.  
            Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formában van megadva, 
            az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) | A bemeneti prezentáció. |
| output_file_name | **str** | A kimeneti fájlnév. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Átalakítja a bemeneti prezentációt JPEG formátumú képek halmazává.  
            Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formában van megadva, 
            az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) | A bemeneti prezentáció |
| output_file_name | **str** | A kimeneti fájlnév. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | Az egyes generált képek mérete. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Átalakítja a bemeneti prezentációt JPEG formátumú képek halmazává.  
            Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formában van megadva, 
            az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) | A bemeneti prezentáció. |
| output_file_name | **str** | A kimeneti fájlnév. |
| scale | **float** | A kimeneti képekre alkalmazott méretezési tényező az eredeti dia méretéhez képest. |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | A renderelési beállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Lásd még
* osztály [`Convert`](/slides/python-net/hu/aspose.slides.lowcode/convert)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* osztály [`Size`](/slides/python-net/hu/aspose.slides/size)
* modul [`aspose.slides.lowcode`](/slides/python-net/hu/aspose.slides.lowcode)
* könyvtár [`Aspose.Slides`](/slides/python-net)