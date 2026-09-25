---
title: to_png method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Konvertiert die Eingabepräsentation in eine Menge von PNG-Bilddateien.  
            Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als eine Menge von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N die Foliennummer ist.


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


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Konvertiert die Eingabepräsentation in eine Menge von PNG-Bilddateien.  
            Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als eine Menge von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N die Foliennummer ist.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation |
| output_file_name | **str** | Der Ausgabedateiname. |
| image_size | [`Size`](/slides/python-net/de/aspose.slides/size) | Die Größe jedes erzeugten Bildes. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konvertiert die Eingabepräsentation in eine Menge von PNG-Bilddateien.  
            Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als eine Menge von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N die Foliennummer ist.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation. |
| output_file_name | **str** | Der Ausgabedateiname. |
| scale | **float** | Der Skalierungsfaktor, der auf die Ausgabebilder im Verhältnis zur Originalfoliengröße angewendet wird. |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Die Rendering-Optionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Siehe Auch
* Klasse [`Convert`](/slides/python-net/de/aspose.slides.lowcode/convert)
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Klasse [`Size`](/slides/python-net/de/aspose.slides/size)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)