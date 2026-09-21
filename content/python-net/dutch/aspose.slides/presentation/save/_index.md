---
title: save method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen.

```python
def save(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/nl/aspose.slides.export.xaml/ixamloptions) | De XAML-indelingsopties. |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.

```python
def save(self, fname, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Pad naar het aangemaakte bestand. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat.

```python
def save(self, stream, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Uitvoerstroom. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) |  |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties.

```python
def save(self, stream, format, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Uitvoerstroom. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Extra indelingsopties. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Als u probeert een versleuteld bestand op te slaan in geen Office 2007-2010-formaat |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummers.

```python
def save(self, fname, slides, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Pad naar het aangemaakte bestand. |
| slides | **List[int]** | Lijst met diapositieposities, beginnend vanaf 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer stream- of slides-parameter None is. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummers.

```python
def save(self, stream, slides, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Uitvoerstroom. |
| slides | **List[int]** | Lijst met diapositieposities, beginnend vanaf 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummers.

```python
def save(self, fname, slides, format, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fname | **str** | Pad naar het aangemaakte bestand. |
| slides | **List[int]** | Lijst met diapositieposities, beginnend vanaf 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Extra indelingsopties. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummers.

```python
def save(self, stream, slides, format, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Uitvoerstroom. |
| slides | **List[int]** | Lijst met diapositieposities, beginnend vanaf 1. |
| format | [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat) | Formaat van de geëxporteerde gegevens. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | Extra indelingsopties. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer stream- of slides-parameter None is. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zie ook
* klasse [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions)
* klasse [`IXamlOptions`](/slides/python-net/nl/aspose.slides.export.xaml/ixamloptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* enumeratie [`SaveFormat`](/slides/python-net/nl/aspose.slides.export/saveformat)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)