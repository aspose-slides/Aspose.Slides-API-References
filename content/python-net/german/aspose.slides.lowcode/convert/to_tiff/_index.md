---
title: to_tiff method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Konvertiert die Eingabepräsentation in eine Menge von Bildern im TIFF-Format.  
            Wenn der Ausgabedateiname als "myPath/myFilename.tiff" angegeben wird, 
            wird das Ergebnis als eine Menge von "myPath/myFilename_N.tiff"-Dateien gespeichert, wobei N die Foliennummer ist.


```python
@staticmethod
def to_tiff(pres, output_file_name):
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


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Konvertiert die Eingabepräsentation in das TIFF-Format mit benutzerdefinierten Optionen.
            Wenn der Ausgabedateiname als "myPath/myFilename.tiff" angegeben wird und `multipage` `false` ist, 
            wird das Ergebnis als eine Menge von "myPath/myFilename_N.tiff"-Dateien gespeichert, wobei N die Foliennummer ist.
            Andernfalls, wenn `multipage` `true` ist, wird das Ergebnis ein mehrseitiges "myPath/myFilename.tiff"-Dokument sein.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die Eingabepräsentation. |
| output_file_name | **str** | Der Ausgabedateiname. |
| options | [`ITiffOptions`](/slides/python-net/de/aspose.slides.export/itiffoptions) | Die TIFF-Speicheroptionen. |
| multipage | **bool** | Gibt an, ob das erzeugte TIFF-Dokument mehrseitig sein soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Siehe auch
* Klasse [`Convert`](/slides/python-net/de/aspose.slides.lowcode/convert)
* Klasse [`ITiffOptions`](/slides/python-net/de/aspose.slides.export/itiffoptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* Bibliothek [`Aspose.Slides`](/slides/python-net)