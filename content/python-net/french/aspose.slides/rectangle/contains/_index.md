---
title: contains method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Détermine si le point spécifié est contenu dans ce rectangle.

### Retour

`True` si le point est contenu dans ce rectangle ; sinon, `False`.



```python
def contains(self, point):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/fr/aspose.slides/point) | Le point à tester. Tout objet possédant les attributs `x` et `y` est accepté. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Nombre d'arguments incorrect. |


## contains(self, rect) {#rectangle}
Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans ce rectangle.

### Retour

`True` si la région rectangulaire représentée par `rect` est entièrement contenue dans ce rectangle ; sinon, `False`.



```python
def contains(self, rect):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/fr/aspose.slides/rectangle) | Le rectangle à tester. Tout objet possédant les attributs `x`, `y`, `width` et `height` est accepté. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Nombre d'arguments incorrect. |


## contains(self, x, y) {#int-int}
Détermine si le point spécifié est contenu dans ce rectangle.

### Retour

`True` si le point défini par `x` et `y` est contenu dans ce rectangle ; sinon, `False`.



```python
def contains(self, x, y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **int** | La coordonnée x du point à tester. |
| y | **int** | La coordonnée y du point à tester. |

### Exceptions

| Exception | Description |
| :- | :- |
| **TypeError** | Nombre d'arguments incorrect. |



### Voir aussi
* classe [`Point`](/slides/python-net/fr/aspose.slides/point)
* classe [`Rectangle`](/slides/python-net/fr/aspose.slides/rectangle)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)