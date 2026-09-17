---
title: get_image method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Devuelve un objeto Thumbnail Image (20% del tamaño real).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
Devuelve un objeto Thumbnail Image con el tamaño especificado.

### Devuelve

Objeto Image.

```python
def get_image(self, image_size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Tamaño de la imagen a crear. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
Devuelve un objeto Thumbnail tiff image con los parámetros especificados.

### Devuelve

Objeto Image.

```python
def get_image(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/es/aspose.slides.export/itiffoptions) | Opciones tiff. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando options.SlideLayoutOption es NotesCommentsLayoutingOptions y su propiedad NotesPosition tiene el valor NotesPositions.BottomFull. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Devuelve un objeto Thumbnail Image.

### Devuelve

Objeto Image.

```python
def get_image(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando notesCommentsLayouting.NotesPosition tiene el valor NotesPositions.BottomFull |

## get_image(self, scale_x, scale_y) {#float-float}
Devuelve un objeto Thumbnail Image con escala personalizada.

### Devuelve

Objeto IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scale_x | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Devuelve un objeto Thumbnail Image con el tamaño especificado.

### Devuelve

Objeto Image.

```python
def get_image(self, options, image_size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| image_size | **aspose.slides.Size** | Tamaño de la imagen a crear. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando options.SlideLayoutOption es NotesCommentsLayoutingOptions y su propiedad NotesPosition tiene el valor NotesPositions.BottomFull. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Devuelve un objeto Thumbnail Image con escala personalizada.

### Devuelve

Objetos Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Opciones de renderizado. |
| scale_x | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scale_y | **float** | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando notesCommentsLayouting.NotesPosition tiene el valor NotesPositions.BottomFull |

### Véase también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`ITiffOptions`](/slides/python-net/es/aspose.slides.export/itiffoptions)
* clase [`Slide`](/slides/python-net/es/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)