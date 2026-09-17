---
title: save method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen.


```python
def save(self, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/de/aspose.slides.export.xaml/ixamloptions) | The XAML format options. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format.


```python
def save(self, fname, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Additional format options. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Wenn versucht wird, eine verschlüsselte Datei im nicht unterstützten Office 2007-2010-Format zu speichern. |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format unter Beibehaltung der Foliennummern.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der stream- oder slides-Parameter None ist. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn der slides-Parameter falsche Foliennummern enthält. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format unter Beibehaltung der Foliennummern.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format unter Beibehaltung der Foliennummern.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Additional format options. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format unter Beibehaltung der Foliennummern.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| format | [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions) | Additional format options. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der stream- oder slides-Parameter None ist. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn der slides-Parameter falsche Foliennummern enthält. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Siehe Auch
* Klasse [`ISaveOptions`](/slides/python-net/de/aspose.slides.export/isaveoptions)
* Klasse [`IXamlOptions`](/slides/python-net/de/aspose.slides.export.xaml/ixamloptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Aufzählung [`SaveFormat`](/slides/python-net/de/aspose.slides.export/saveformat)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)