---
title: save method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Slaat de afbeelding op in een bestand.

```python
def save(self, filename):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| filename | **str** | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |

## save(self, filename, format) {#str-imageformat}
Slaat de afbeelding op in een bestand in het opgegeven formaat.

```python
def save(self, filename, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| filename | **str** | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |
| format | [`ImageFormat`](/slides/python-net/nl/aspose.slides/imageformat) | Het afbeeldingsformaat. |

## save(self, stream, format) {#iorawiobase-imageformat}
Slaat de afbeelding op in een stream in het opgegeven formaat.

```python
def save(self, stream, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | De stream waarin de afbeelding wordt opgeslagen. |
| format | [`ImageFormat`](/slides/python-net/nl/aspose.slides/imageformat) | Het afbeeldingsformaat. |

## save(self, filename, format, quality) {#str-imageformat-int}
Slaat de afbeelding op in een bestand in het opgegeven formaat en kwaliteit.

```python
def save(self, filename, format, quality):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| filename | **str** | Het pad naar het bestand waarin de afbeelding wordt opgeslagen. |
| format | [`ImageFormat`](/slides/python-net/nl/aspose.slides/imageformat) | Het afbeeldingsformaat. |
| quality | **int** | De kwaliteit van de opgeslagen afbeelding (0 tot 100).  <br/><br/>            Deze parameter heeft alleen invloed op het opslaan in [`ImageFormat.JPEG`](/slides/python-net/nl/aspose.slides/imageformat/JPEG); voor alle andere formaten wordt hij genegeerd. |

## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Slaat de afbeelding op in een stream in het opgegeven formaat en kwaliteit.

```python
def save(self, stream, format, quality):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | De stream waarin de afbeelding wordt opgeslagen. |
| format | [`ImageFormat`](/slides/python-net/nl/aspose.slides/imageformat) | Het afbeeldingsformaat. |
| quality | **int** | De kwaliteit van de opgeslagen afbeelding (0 tot 100).  <br/><br/>            Deze parameter heeft alleen invloed op het opslaan in [`ImageFormat.JPEG`](/slides/python-net/nl/aspose.slides/imageformat/JPEG); voor alle andere formaten wordt hij genegeerd. |

### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeratie [`ImageFormat`](/slides/python-net/nl/aspose.slides/imageformat)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)