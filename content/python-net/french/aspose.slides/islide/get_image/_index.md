---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
Renvoie un objet Image miniature (20 % de la taille réelle).

### Renvoie

Objet Image **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Renvoie un objet image avec la taille spécifiée.

### Renvoie

Objet Bitmap.



```python
def get_image(self, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | Taille de l'image à créer. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Renvoie un objet bitmap tiff miniature avec les paramètres spécifiés.

### Renvoie

Objet Image.



```python
def get_image(self, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions) | Options Tiff. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Renvoie un objet Bitmap miniature.

### Renvoie

Objets Bitmap.



```python
def get_image(self, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |


## get_image(self, scale_x, scale_y) {#float-float}
Renvoie un objet image avec un redimensionnement personnalisé.

### Renvoie

Objet Image **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| scale_x | **float** | Valeur par laquelle mettre à l'échelle cette miniature sur l'axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l'échelle cette miniature sur l'axe y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Renvoie un objet Bitmap miniature avec la taille spécifiée.

### Renvoie

Objets Bitmap.



```python
def get_image(self, options, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | Taille de l'image à créer. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Renvoie un objet Bitmap miniature avec un redimensionnement personnalisé.

### Renvoie

Objets Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| scale_x | **float** | Valeur par laquelle mettre à l'échelle cette miniature sur l'axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l'échelle cette miniature sur l'axe y. |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`ITiffOptions`](/slides/python-net/fr/aspose.slides.export/itiffoptions)
* classe [`Size`](/slides/python-net/fr/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)