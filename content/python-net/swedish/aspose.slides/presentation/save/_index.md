---
title: save method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentation/save/
weight: 100
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup.


```python
def save(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/sv/aspose.slides.export.xaml/ixamloptions) | The XAML format options. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Sparar alla bilder i en presentation till en fil med det angivna formatet.


```python
def save(self, fname, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Sparar alla bilder i en presentation till en ström i det angivna formatet.


```python
def save(self, stream, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Om du försöker spara en krypterad fil i <br/>            något Office 2007-2010-format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnummer-behållning.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När parametern stream eller slides är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | När slides-parametern innehåller fel sidnummer. |
| **RuntimeError(Proxy error(InvalidOperationException))** | När ett ej stödformat SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Sparar angivna bilder i en presentation till en ström i det angivna formatet med sidnummer-behållning.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnummer-behållning.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Additional format options. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar angivna bilder i en presentation till en ström i det angivna formatet med sidnummer-behållning.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När parametern stream eller slides är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | När slides-parametern innehåller fel sidnummer. |
| **RuntimeError(Proxy error(InvalidOperationException))** | När ett ej stödformat SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### See Also
* klass [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions)
* klass [`IXamlOptions`](/slides/python-net/sv/aspose.slides.export.xaml/ixamloptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* enumeration [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)