---
title: from_argb method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Maakt een kleur van een 32-bit ARGB-waarde.

### Retour

De kleur die is gecreëerd uit de opgegeven waarde.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb | **int** | Een waarde die de 32-bit ARGB-waarde specificeert (ondertekend of zonder teken). |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **ValueError** | Een componentwaarde is kleiner dan 0 of groter dan 255. |
| **TypeError** | Onjuist aantal of type argumenten. |


## from_argb(alpha, base_color) {#int-color}
Maakt een kleur van de opgegeven alpha-waarde en basiskleur.

### Retour

De kleur die is gecreëerd uit de opgegeven waarden.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alpha | **int** | De alpha componentwaarde. Geldige waarden zijn 0 tot en met 255. |
| base_color | [`Color`](/slides/python-net/nl/aspose.slides/color) | De kleur waaruit de nieuwe kleur wordt gemaakt. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **ValueError** | Een componentwaarde is kleiner dan 0 of groter dan 255. |
| **TypeError** | Onjuist aantal of type argumenten. |


## from_argb(red, green, blue) {#int-int-int}
Maakt een ondoorzichtige kleur (alpha is 255) van de opgegeven rood, groen en blauw waarden.

### Retour

De kleur die is gecreëerd uit de opgegeven waarden.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| red | **int** | De red componentwaarde. Geldige waarden zijn 0 tot en met 255. |
| green | **int** | De green componentwaarde. Geldige waarden zijn 0 tot en met 255. |
| blue | **int** | De blue componentwaarde. Geldige waarden zijn 0 tot en met 255. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **ValueError** | Een componentwaarde is kleiner dan 0 of groter dan 255. |
| **TypeError** | Onjuist aantal of type argumenten. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Maakt een kleur van de vier ARGB-componentwaarden (alpha, red, green en blue).

### Retour

De kleur die is gecreëerd uit de opgegeven waarden.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alpha | **int** | De alpha componentwaarde. Geldige waarden zijn 0 tot en met 255. |
| red | **int** | De red componentwaarde. Geldige waarden zijn 0 tot en met 255. |
| green | **int** | De green componentwaarde. Geldige waarden zijn 0 tot en met 255. |
| blue | **int** | De blue componentwaarde. Geldige waarden zijn 0 tot en met 255. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **ValueError** | Een componentwaarde is kleiner dan 0 of groter dan 255. |
| **TypeError** | Onjuist aantal of type argumenten. |



### Zie ook
* klasse [`Color`](/slides/python-net/nl/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)