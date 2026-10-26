---
title: equals method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Détermine si les deux instances d'IBaseSlide sont égales.
            La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique.
            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont identiques. La comparaison ne prend pas en compte les valeurs des identifiants uniques, par exemple SlideId, ni le contenu dynamique, par exemple la valeur de la date actuelle dans l'espace réservé de date.

### Retour

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
* classe [`MasterNotesSlide`](/slides/python-net/fr/aspose.slides/masternotesslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)