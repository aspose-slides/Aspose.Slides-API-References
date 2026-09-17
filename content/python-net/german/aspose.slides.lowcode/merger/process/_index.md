---
title: process method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_file_names | **List[str]** | Ein Array mit den Eingabedateinamen der Präsentation. |
| output_file_name | **str** | Der Ausgabedateiname der resultierenden zusammengeführten Präsentationsdatei. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn Eingabedateinamen ungültig sind oder Formate nicht übereinstimmen. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_file_names | **List[str]** | Ein Array mit den Eingabedateinamen der Präsentation. |
| output_stream | **io.RawIOBase** | Der Ausgabestream. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn Eingabedateinamen ungültig sind oder Formate nicht übereinstimmen. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_file_names | **List[str]** | Ein Array mit den Eingabedateinamen der Präsentation. |
| output_file_name | **str** | Der Ausgabedateiname der resultierenden zusammengeführten Präsentationsdatei. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Die zusätzlichen Optionen, die bestimmen, wie die zusammengeführte Präsentation gespeichert wird. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn Eingabedateinamen ungültig sind oder Formate nicht übereinstimmen. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_file_names | **List[str]** | Ein Array mit den Eingabedateinamen der Präsentation. |
| output_stream | **io.RawIOBase** | Der Ausgabestream. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Die zusätzlichen Optionen, die bestimmen, wie die zusammengeführte Präsentation gespeichert wird. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn Eingabedateinamen ungültig sind oder Formate nicht übereinstimmen. |

### Siehe auch
* Klasse [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions)
* Klasse [`Merger`](/slides/python-net/de/aspose.slides.lowcode/merger)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* Bibliothek [`Aspose.Slides`](/slides/python-net)