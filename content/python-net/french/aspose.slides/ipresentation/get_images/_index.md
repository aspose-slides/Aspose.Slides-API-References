---
title: get_images method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Renvoie des objets Image miniature pour toutes les diapositives d’une présentation.

### Retour

objets Bitmap.



```python
def get_images(self, options):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Renvoie des objets Bitmap miniature pour les diapositives spécifiées d’une présentation.

### Retour

objets Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| slides | **List[int]** | Tableau avec les positions des diapositives, à partir de 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec la taille spécifiée.

### Retour

objets Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| image_size | **aspose.slides.Size** | Taille de l’image à créer. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec un redimensionnement personnalisé.

### Retour

objets Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| scale_x | **float** | Valeur par laquelle mettre à l’échelle cette miniature dans la direction de l’axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l’échelle cette miniature dans la direction de l’axe y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec la taille spécifiée.

### Retour

objets Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| slides | **List[int]** | Tableau avec les positions des diapositives, à partir de 1. |
| image_size | **aspose.slides.Size** | Taille de l’image à créer. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec un redimensionnement personnalisé.

### Retour

objets Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options de rendu. |
| slides | **List[int]** | Tableau avec les positions des diapositives, à partir de 1. |
| scale_x | **float** | Valeur par laquelle mettre à l’échelle cette miniature dans la direction de l’axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l’échelle cette miniature dans la direction de l’axe y. |



### Voir aussi
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* classe [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)