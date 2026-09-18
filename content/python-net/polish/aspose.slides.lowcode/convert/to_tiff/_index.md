---
title: to_tiff method
second_title: Referencja API Aspose.Slides dla Pythona przez .NET
description: 
type: docs
url: /pl/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Konwertuje podaną prezentację do zestawu obrazów w formacie TIFF.  
Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.tiff", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Wejściowa prezentacja. |
| output_file_name | **str** | Nazwa pliku wyjściowego. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Konwertuje podaną prezentację do formatu TIFF z niestandardowymi opcjami.  
Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.tiff" i `multipage` jest `false`, wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu.  
W przeciwnym razie, jeśli `multipage` jest `true`, wynik będzie dokumentem wielostronicowym "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Wejściowa prezentacja. |
| output_file_name | **str** | Nazwa pliku wyjściowego. |
| options | [`ITiffOptions`](/slides/python-net/pl/aspose.slides.export/itiffoptions) | Opcje zapisu TIFF. |
| multipage | **bool** | Określa, czy wygenerowany dokument TIFF ma być wielostronicowy. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Zobacz także
* klasa [`Convert`](/slides/python-net/pl/aspose.slides.lowcode/convert)
* klasa [`ITiffOptions`](/slides/python-net/pl/aspose.slides.export/itiffoptions)
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)