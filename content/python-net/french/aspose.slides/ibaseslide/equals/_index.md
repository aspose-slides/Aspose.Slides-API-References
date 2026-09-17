---
title: equals method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ibaseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Détermine si les deux instances d'IBaseSlide sont égales.
            La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique.
            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par exemple SlideId, et le contenu dynamique, par exemple la valeur de date actuelle dans le caractère générique de date.

### Returns

**true**  si le IBaseSlide spécifié est égal au IBaseSlide actuel ; 
            sinon, **false** .

```python
def equals(self, slide):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | Le IBaseSlide à comparer avec le IBaseSlide actuel. |

### See Also
* classe [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)