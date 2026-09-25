---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Renvoie un objet Thumbnail Image (20% de la taille réelle).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Renvoie un objet Thumbnail Image avec la taille spécifiée.

### Renvoie

Objet Image.



```python
def get_image(self, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | Taille de l'image à créer. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Renvoie un objet Thumbnail tiff image avec les paramètres spécifiés.

### Renvoie

Objet Image.



```python
def get_image(self, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions) | Options Tiff. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Levée lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et que sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Renvoie un objet Thumbnail Image.

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
| **RuntimeError(Proxy error(InvalidOperationException))** | Levée lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé.

### Renvoie

Objet IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| scale_x | **float** | Valeur par laquelle mettre à l'échelle ce Thumbnail sur l'axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l'échelle ce Thumbnail sur l'axe y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Renvoie un objet Thumbnail Image avec la taille spécifiée.

### Renvoie

Objet Image.



```python
def get_image(self, options, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | Taille de l'image à créer. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Levée lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et que sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Renvoie un objet Thumbnail Image avec un redimensionnement personnalisé.

### Renvoie

Objets Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| scale_x | **float** | Valeur par laquelle mettre à l'échelle ce Thumbnail sur l'axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l'échelle ce Thumbnail sur l'axe y. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Levée lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull. |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* classe [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions)
* classe [`Slide`](/slides/python-net/fr/aspose.slides/slide)
* classe [`Size`](/slides/python-net/fr/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)