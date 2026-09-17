---
title: get_images method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Renvoie des Image objects pour toutes les diapositives d’une présentation.

### Retour

Image objects.



```python
def get_images(self, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Renvoie des Image objects vignettes pour les diapositives spécifiées d’une présentation.

### Retour

Image objects.



```python
def get_images(self, options, slides):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| slides | **List[int]** | Tableau avec les positions des diapositives, à partir de 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Renvoie des Image objects vignettes pour toutes les diapositives d’une présentation avec la taille spécifiée.

### Retour

Image objects.



```python
def get_images(self, options, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| image_size | **aspose.slides.Size** | Taille de l’image à créer. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Renvoie des Image objects vignettes pour toutes les diapositives d’une présentation avec un redimensionnement personnalisé.

### Retour

Image objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| scale_x | **float** | Valeur par laquelle mettre à l’échelle cette vignette dans la direction de l’axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l’échelle cette vignette dans la direction de l’axe y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Renvoie des Image objects vignettes pour les diapositives spécifiées d’une présentation avec la taille spécifiée.

### Retour

Image objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| slides | **List[int]** | Tableau avec les positions des diapositives, à partir de 1. |
| image_size | **aspose.slides.Size** | Taille de l’image à créer. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Renvoie des Image objects vignettes pour les diapositives spécifiées d’une présentation avec un redimensionnement personnalisé.

### Retour

Image objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| slides | **List[int]** | Tableau avec les positions des diapositives, à partir de 1. |
| scale_x | **float** | Valeur par laquelle mettre à l’échelle cette vignette dans la direction de l’axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l’échelle cette vignette dans la direction de l’axe y. |



### Voir aussi
* class [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* class [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)