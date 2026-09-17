---
title: to_png method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Konvertiert die Eingabepräsentation in eine Menge von PNG-Format-Bildern.  
            Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, 
            wird das Ergebnis als Menge von "myPath/myFilename_N.png" Dateien gespeichert, wobei N eine Foliennummer ist.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation. |
| output_file_name | **str** | Der Ausgabedateiname. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Konvertiert die Eingabepräsentation in eine Menge von PNG-Format-Bildern.  
            Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, 
            wird das Ergebnis als Menge von "myPath/myFilename_N.png" Dateien gespeichert, wobei N eine Foliennummer ist.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation |
| output_file_name | **str** | Der Ausgabedateiname. |
| image_size | **aspose.slides.Size** | Die Größe jedes erzeugten Bildes. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konvertiert die Eingabepräsentation in eine Menge von PNG-Format-Bildern.  
            Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, 
            wird das Ergebnis als Menge von "myPath/myFilename_N.png" Dateien gespeichert, wobei N eine Foliennummer ist.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation. |
| output_file_name | **str** | Der Ausgabedateiname. |
| scale | **float** | Der Skalierungsfaktor, der auf die Ausgabebilder relativ zur Originalfoliengröße angewendet wird. |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Die Renderoptionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Siehe auch
* class [`Convert`](/slides/python-net/de/aspose.slides.lowcode/convert)
* class [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* class [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)