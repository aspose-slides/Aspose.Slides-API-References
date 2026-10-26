---
title: save method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Slaat alle dia's van een presentatie op naar een reeks bestanden die XAML-markup vertegenwoordigen.


```python
def save(self, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/nl/aspose.slides.export.xaml/ixamloptions) | The XAML format options. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat.


```python
def save(self, fname, format):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat en met extra opties.


```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Additional format options. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat en met extra opties.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Als u probeert een versleuteld bestand op te slaan in geen Office 2007-2010-formaat |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Slaat opgegeven dia's van een presentatie op naar een bestand met het opgegeven formaat.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |

### Exceptions

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer de stream- of slides-parameter None is. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Slaat opgegeven dia's van een presentatie op naar een stream in het opgegeven formaat.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |

### Exceptions

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer de stream- of slides-parameter None is. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat opgegeven dia's van een presentatie op naar een bestand met het opgegeven formaat.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer de stream- of slides-parameter None is. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat opgegeven dia's van een presentatie op naar een stream in het opgegeven formaat.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer de stream- of slides-parameter None is. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Zie ook
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* klasse [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions)
* klasse [`IXamlOptions`](/slides/python-net/nl/aspose.slides.export.xaml/ixamloptions)
* enumeratie [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)