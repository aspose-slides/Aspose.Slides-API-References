---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Renvoie un objet Image miniature (20% de la taille réelle).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
Renvoie un objet Image miniature avec la taille spécifiée.

### Renvoie
Objet Image.

```python
def get_image(self, image_size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Taille de l'image à créer. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
Renvoie un objet image tiff miniature avec les paramètres spécifiés.

### Renvoie
Objet Image.

```python
def get_image(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions) | Options tiff. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancé lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et que sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Renvoie un objet Image miniature.

### Renvoie
Objet Image.

```python
def get_image(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancé lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull |

## get_image(self, scale_x, scale_y) {#float-float}
Renvoie un objet Image miniature avec un redimensionnement personnalisé.

### Renvoie
Objet IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| scale_x | **float** | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe x. |
| scale_y | **float** | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe y. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Renvoie un objet Image miniature avec la taille spécifiée.

### Renvoie
Objet Image.

```python
def get_image(self, options, image_size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| image_size | **aspose.slides.Size** | Taille de l'image à créer. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancé lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et que sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Renvoie un objet Image miniature avec un redimensionnement personnalisé.

### Renvoie
Objets Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| scale_x | **float** | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe x. |
| scale_y | **float** | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe y. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancé lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull |

### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* classe [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions)
* classe [`Slide`](/slides/python-net/fr/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)