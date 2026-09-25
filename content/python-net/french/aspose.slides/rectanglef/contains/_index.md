---
title: contains method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Détermine si le point spécifié est contenu dans ce rectangle.

### Valeur de retour

`True` si le point est contenu dans ce rectangle ; sinon, `False`.



```python
def contains(self, point):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/fr/aspose.slides/pointf) | Le point à tester. Tout objet possédant les attributs `x` et `y` est accepté. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Nombre d'arguments incorrect. |


## contains(self, rect) {#rectanglef}
Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans ce rectangle.

### Valeur de retour

`True` si la région rectangulaire représentée par `rect` est entièrement contenue dans ce rectangle ; sinon, `False`.



```python
def contains(self, rect):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef) | Le rectangle à tester. Tout objet possédant les attributs `x`, `y`, `width` et `height` est accepté. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Nombre d'arguments incorrect. |


## contains(self, x, y) {#float-float}
Détermine si le point spécifié est contenu dans ce rectangle.

### Valeur de retour

`True` si le point défini par `x` et `y` est contenu dans ce rectangle ; sinon, `False`.



```python
def contains(self, x, y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du point à tester. |
| y | **float** | La coordonnée y du point à tester. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Nombre d'arguments incorrect. |



### Voir aussi
* classe [`PointF`](/slides/python-net/fr/aspose.slides/pointf)
* classe [`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)