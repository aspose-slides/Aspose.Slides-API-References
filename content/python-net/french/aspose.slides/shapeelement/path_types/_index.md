---
title: path_types property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types propriété
Renvoie un tableau de valeurs byte qui spécifient le type de chaque point dans le chemin de l'élément. 
            
**0**  Indique que le point est le début d'une figure.


**1**  Indique que le point est l'un des deux points d'extrémité d'une ligne.


**3**  Indique que le point est un point d'extrémité ou un point de contrôle d'une spline cubique de Bézier.


**7**  Masque tous les bits sauf les trois bits de poids faible, qui indiquent le type de point.


**16**  Indique que le segment correspondant est en pointillés.


**32**  Indique que le point est un marqueur.


**128**  Indique que le point est le dernier point d'un sous-chemin fermé (figure).


**129**  Indique un point de données qui est à la fois le point d'extrémité d'un segment de ligne et le dernier point d'un sous-chemin fermé.

### Définition:
```python
@property
def path_types(self):
    ...
```


### Voir aussi
* classe [`ShapeElement`](/slides/python-net/fr/aspose.slides/shapeelement)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)