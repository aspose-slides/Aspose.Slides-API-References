---
title: to_jpeg method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Konvertiert die Eingabepräsentation in eine Menge von JPEG-Format-Bildern.  
Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als eine Menge von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N eine Foliennummer ist.

```python
@staticmethod
def to_jpeg(pres, output_file_name):
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

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Konvertiert die Eingabepräsentation in eine Menge von JPEG-Format-Bildern.  
Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als eine Menge von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N eine Foliennummer ist.

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
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

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konvertiert die Eingabepräsentation in eine Menge von JPEG-Format-Bildern.  
Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als eine Menge von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N eine Foliennummer ist.

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation. |
| output_file_name | **str** | Der Ausgabedateiname. |
| scale | **float** | Der Skalierungsfaktor, der auf die Ausgabebilder relativ zur Originalfoliengröße angewendet wird. |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Die Rendering-Optionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### Siehe auch
* Klasse [`Convert`](/slides/python-net/de/aspose.slides.lowcode/convert)
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* Bibliothek [`Aspose.Slides`](/slides/python-net)