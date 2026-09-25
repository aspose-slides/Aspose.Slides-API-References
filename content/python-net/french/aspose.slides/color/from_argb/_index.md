---
title: from_argb method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Crée une couleur à partir d'une valeur ARGB de 32 bits.

### Valeur de retour

La couleur créée à partir de la valeur spécifiée.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| argb | **int** | Une valeur spécifiant la valeur ARGB de 32 bits (signée ou non signée). |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Une valeur de composant est inférieure à 0 ou supérieure à 255. |
| **TypeError** | Nombre ou type d'arguments incorrect. |


## from_argb(alpha, base_color) {#int-color}
Crée une couleur à partir de la valeur alpha spécifiée et de la couleur de base.

### Valeur de retour

La couleur créée à partir des valeurs spécifiées.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| alpha | **int** | La valeur du composant alpha. Les valeurs valides sont de 0 à 255. |
| base_color | [`Color`](/slides/python-net/fr/aspose.slides/color) | La couleur à partir de laquelle créer la nouvelle couleur. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Une valeur de composant est inférieure à 0 ou supérieure à 255. |
| **TypeError** | Nombre ou type d'arguments incorrect. |


## from_argb(red, green, blue) {#int-int-int}
Crée une couleur opaque (alpha vaut 255) à partir des valeurs rouge, vert et bleu spécifiées.

### Valeur de retour

La couleur créée à partir des valeurs spécifiées.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| red | **int** | La valeur du composant rouge. Les valeurs valides sont de 0 à 255. |
| green | **int** | La valeur du composant vert. Les valeurs valides sont de 0 à 255. |
| blue | **int** | La valeur du composant bleu. Les valeurs valides sont de 0 à 255. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Une valeur de composant est inférieure à 0 ou supérieure à 255. |
| **TypeError** | Nombre ou type d'arguments incorrect. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Crée une couleur à partir des quatre valeurs des composants ARGB (alpha, rouge, vert et bleu).

### Valeur de retour

La couleur créée à partir des valeurs spécifiées.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| alpha | **int** | La valeur du composant alpha. Les valeurs valides sont de 0 à 255. |
| red | **int** | La valeur du composant rouge. Les valeurs valides sont de 0 à 255. |
| green | **int** | La valeur du composant vert. Les valeurs valides sont de 0 à 255. |
| blue | **int** | La valeur du composant bleu. Les valeurs valides sont de 0 à 255. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Une valeur de composant est inférieure à 0 ou supérieure à 255. |
| **TypeError** | Nombre ou type d'arguments incorrect. |



### Voir aussi
* classe [`Color`](/slides/python-net/fr/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)