---
title: get_images method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Retourneert een Thumbnail Image objecten voor alle dia's van een presentatie.

### Returns
Bitmap objecten.

```python
def get_images(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Renderopties. |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Retourneert een Thumbnail Bitmap objecten voor gespecificeerde dia's van een presentatie.

### Returns
Bitmap objecten.

```python
def get_images(self, options, slides):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Renderopties. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Retourneert een Thumbnail Image objecten voor alle dia's van een presentatie met opgegeven grootte.

### Returns
Bitmap objecten.

```python
def get_images(self, options, image_size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Renderopties. |
| image_size | **aspose.slides.Size** | Grootte van de afbeelding die moet worden gemaakt. |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retourneert een Thumbnail Image objecten voor alle dia's van een presentatie met aangepaste schaal.

### Returns
Bitmap objecten.

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Renderopties. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingssize}
Retourneert een Thumbnail Image objecten voor gespecificeerde dia's van een presentatie met opgegeven grootte.

### Returns
Bitmap objecten.

```python
def get_images(self, options, slides, image_size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Renderopties. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |
| image_size | **aspose.slides.Size** | Grootte van de afbeelding die moet worden gemaakt. |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Retourneert een Thumbnail Image objecten voor gespecificeerde dia's van een presentatie met aangepaste schaal.

### Returns
Bitmap objecten.

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Renderopties. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### See Also
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)