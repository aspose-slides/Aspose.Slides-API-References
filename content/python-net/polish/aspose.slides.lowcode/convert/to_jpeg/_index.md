---
title: to_jpeg method
second_title: Aspose.Slides dla Pythona przez interfejs .NET API
description: 
type: docs
url: /pl/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG.  
Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Prezentacja wejściowa. |
| output_file_name | **str** | Nazwa pliku wyjściowego. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG.  
Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Prezentacja wejściowa |
| output_file_name | **str** | Nazwa pliku wyjściowego. |
| image_size | **aspose.slides.Size** | Rozmiar każdego wygenerowanego obrazu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG.  
Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Prezentacja wejściowa. |
| output_file_name | **str** | Nazwa pliku wyjściowego. |
| scale | **float** | Współczynnik skalowania zastosowany do obrazów wyjściowych względem oryginalnego rozmiaru slajdu. |
| options | [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions) | Opcje renderowania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### Zobacz także
* klasa [`Convert`](/slides/python-net/pl/aspose.slides.lowcode/convert)
* klasa [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions)
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)