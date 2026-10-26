---
title: equals method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Détermine si les deux instances d'IBaseSlide sont égales.
            La valeur renvoyée est calculée en fonction de la structure de la diapositive et de son contenu statique.
            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par ex. SlideId, ni le contenu dynamique, par ex. la valeur de la date actuelle dans le texte de remplacement de date.

### Renvoie

**true**  si l'IBaseSlide spécifié est égal à l'IBaseSlide actuel ; 
            sinon, **false** .


```python
def equals(self, slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | L'IBaseSlide à comparer avec l'IBaseSlide actuel. |


### Voir aussi
* classe [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide)
* classe [`MasterHandoutSlide`](/slides/python-net/fr/aspose.slides/masterhandoutslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)