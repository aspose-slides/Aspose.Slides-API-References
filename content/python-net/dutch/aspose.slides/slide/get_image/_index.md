---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Retourneert een Thumbnail Image object (20% van de werkelijke grootte).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposeslidessize}
Retourneert een Thumbnail Image object met de opgegeven grootte.

### Retourwaarde
Image object.

```python
def get_image(self, image_size):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | Grootte van de afbeelding die moet worden gemaakt. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
Retourneert een Thumbnail tiff image object met opgegeven parameters.

### Retourwaarde
Image object.

```python
def get_image(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/nl/aspose.slides.export/itiffoptions) | Tiff opties. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer options.SlideLayoutOption NotesCommentsLayoutingOptions is en zijn eigenschap NotesPosition de waarde NotesPositions.BottomFull aanneemt. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Retourneert een Thumbnail Image object.

### Retourwaarde
Image object.

```python
def get_image(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering opties. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer notesCommentsLayouting.NotesPosition de waarde NotesPositions.BottomFull aanneemt. |

## get_image(self, scale_x, scale_y) {#float-float}
Retourneert een Thumbnail Image object met aangepaste schaal.

### Retourwaarde
IImage object.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Retourneert een Thumbnail Image object met de opgegeven grootte.

### Retourwaarde
Image object.

```python
def get_image(self, options, image_size):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering opties. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | Grootte van de afbeelding die moet worden gemaakt. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer options.SlideLayoutOption NotesCommentsLayoutingOptions is en zijn eigenschap NotesPosition de waarde NotesPositions.BottomFull aanneemt. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retourneert een Thumbnail Image object met aangepaste schaal.

### Retourwaarde
Bitmap objecten.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering opties. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer notesCommentsLayouting.NotesPosition de waarde NotesPositions.BottomFull aanneemt. |

### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`ITiffOptions`](/slides/python-net/nl/aspose.slides.export/itiffoptions)
* klasse [`Slide`](/slides/python-net/nl/aspose.slides/slide)
* klasse [`Size`](/slides/python-net/nl/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)