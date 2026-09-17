---
title: equals method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Détermine si les deux instances de IBaseSlide sont égales.  
La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique.  
Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne tient pas compte des valeurs d’identifiants uniques, par exemple SlideId, ni du contenu dynamique, par exemple la valeur de date courante dans le texte de substitution Date.

### Valeur retournée

**true**  si l’IBaseSlide spécifié est égal à l’IBaseSlide actuel ;  
sinon, **false** .



```python
def equals(self, slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | L’IBaseSlide à comparer avec l’IBaseSlide actuel. |



### Voir aussi
* classe [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide)
* classe [`Slide`](/slides/python-net/fr/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)