---
title: to_png method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Konwertuje podaną prezentację na zestaw obrazów w formacie PNG.  
            Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.png", 
            wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Podana prezentacja. |
| output_file_name | **str** | Nazwa pliku wyjściowego. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Konwertuje podaną prezentację na zestaw obrazów w formacie PNG.  
            Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.png", 
            wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Podana prezentacja |
| output_file_name | **str** | Nazwa pliku wyjściowego. |
| image_size | **aspose.slides.Size** | Rozmiar każdego generowanego obrazu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konwertuje podaną prezentację na zestaw obrazów w formacie PNG.  
            Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.png", 
            wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Podana prezentacja. |
| output_file_name | **str** | Nazwa pliku wyjściowego. |
| scale | **float** | Współczynnik skalowania stosowany do obrazów wyjściowych w stosunku do oryginalnego rozmiaru slajdu. |
| options | [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions) | Opcje renderowania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Zobacz też
* klasa [`Convert`](/slides/python-net/pl/aspose.slides.lowcode/convert)
* klasa [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions)
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)