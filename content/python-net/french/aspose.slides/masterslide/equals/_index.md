---
title: equals method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
Détermine si les deux instances IBaseSlide sont égales.
            La valeur de retour est calculée en fonction de la structure et du contenu statique de la diapositive.
            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par exemple SlideId, et du contenu dynamique, par exemple la valeur de date actuelle dans le texte de remplacement Date.

### Valeur de retour

**true** si l'IBaseSlide spécifié est égal à l'IBaseSlide actuel ; sinon, **false** .



```python
def equals(self, slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | L'IBaseSlide à comparer avec l'IBaseSlide actuel. |



### Voir aussi
* classe [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide)
* classe [`MasterSlide`](/slides/python-net/fr/aspose.slides/masterslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)