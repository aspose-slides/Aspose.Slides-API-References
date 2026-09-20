---
title: save method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup.


```python
def save(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/sv/aspose.slides.export.xaml/ixamloptions) | Alternativen för XAML-formatet. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Sparar alla bilder i en presentation till en fil med det angivna formatet.


```python
def save(self, fname, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Sökväg till den skapade filen. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Sparar alla bilder i en presentation till en ström i det angivna formatet.


```python
def save(self, stream, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Utmatningsström. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ.


```python
def save(self, fname, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Sökväg till den skapade filen. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Ytterligare formatalternativ. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Utmatningsström. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Ytterligare formatalternativ. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Om du försöker spara en krypterad fil i <br/>            ingen Office 2007-2010-format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Sparar angivna bilder i en presentation till en fil med det angivna formatet.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Sökväg till den skapade filen. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När stream- eller slides-parameter är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | När slides-parameter innehåller fel sidnummer. |
| **RuntimeError(Proxy error(InvalidOperationException))** | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Sparar angivna bilder i en presentation till en ström i det angivna formatet.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Utmatningsström. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När stream- eller slides-parameter är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | När slides-parameter innehåller fel sidnummer. |
| **RuntimeError(Proxy error(InvalidOperationException))** | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar angivna bilder i en presentation till en fil med det angivna formatet.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fname | **str** | Sökväg till den skapade filen. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Ytterligare formatalternativ. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När stream- eller slides-parameter är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | När slides-parameter innehåller fel sidnummer. |
| **RuntimeError(Proxy error(InvalidOperationException))** | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Sparar angivna bilder i en presentation till en ström i det angivna formatet.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Utmatningsström. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |
| format | [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat) | Format för de exporterade data. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | Ytterligare formatalternativ. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När stream- eller slides-parameter är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | När slides-parameter innehåller fel sidnummer. |
| **RuntimeError(Proxy error(InvalidOperationException))** | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Se också
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* klass [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions)
* klass [`IXamlOptions`](/slides/python-net/sv/aspose.slides.export.xaml/ixamloptions)
* enumeration [`SaveFormat`](/slides/python-net/sv/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)