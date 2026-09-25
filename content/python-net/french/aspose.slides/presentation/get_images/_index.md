---
title: get_images method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Renvoie des objets Image pour toutes les diapositives d'une présentation.

### Renvoie
Objets Image.

```python
def get_images(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Renvoie des objets Thumbnail Image pour les diapositives spécifiées d'une présentation.

### Renvoie
Objets Image.

```python
def get_images(self, options, slides):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Renvoie des objets Thumbnail Image pour toutes les diapositives d'une présentation avec la taille spécifiée.

### Renvoie
Objets Image.

```python
def get_images(self, options, image_size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | Taille de l'image à créer. |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Renvoie des objets Thumbnail Image pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé.

### Renvoie
Objets Image.

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| scale_x | **float** | Valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe y. |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Renvoie des objets Thumbnail Image pour les diapositives spécifiées d'une présentation avec la taille spécifiée.

### Renvoie
Objets Image.

```python
def get_images(self, options, slides, image_size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |
| image_size | [`Size`](/slides/python-net/fr/aspose.slides/size) | Taille de l'image à créer. |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Renvoie des objets Thumbnail Image pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé.

### Renvoie
Objets Image.

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions) | Options Tiff. |
| slides | **List[int]** | Tableau contenant les positions des diapositives, à partir de 1. |
| scale_x | **float** | Valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe x. |
| scale_y | **float** | Valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe y. |

### Voir aussi
* classe [`IRenderingOptions`](/slides/python-net/fr/aspose.slides.export/irenderingoptions)
* classe [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* classe [`Size`](/slides/python-net/fr/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)