---
title: save method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen.


```python
def save(self, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/de/aspose.slides.export.xaml/ixamloptions) | Die XAML-Formatoptionen. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format.


```python
def save(self, fname, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Pfad zur erstellten Datei. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ausgabestream. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format und zusätzlichen Optionen.


```python
def save(self, fname, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Pfad zur erstellten Datei. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Zusätzliche Formatoptionen. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ausgabestream. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Wenn Sie versuchen, eine verschlüsselte Datei im <br/>            Nicht-Office-2007-2010-Format zu speichern |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Pfad zur erstellten Datei. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der Parameter stream oder slides None ist. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn der slides-Parameter falsche Seitennummern enthält. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ausgabestream. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der Parameter stream oder slides None ist. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn der slides-Parameter falsche Seitennummern enthält. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Pfad zur erstellten Datei. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der Parameter stream oder slides None ist. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn der slides-Parameter falsche Seitennummern enthält. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ausgabestream. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format der exportierten Daten. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der Parameter stream oder slides None ist. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn der slides-Parameter falsche Seitennummern enthält. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Siehe auch
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Klasse [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions)
* Klasse [`IXamlOptions`](/slides/python-net/de/aspose.slides.export.xaml/ixamloptions)
* Aufzählung [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)