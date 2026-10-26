---
title: equals method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Détermine si les deux instances d'IBaseSlide sont égales.
            La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique.
            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont identiques. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par ex. SlideId et du contenu dynamique, par ex. la valeur de date actuelle dans le texte de substitution de date.

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
* classe [`NotesSlide`](/slides/python-net/fr/aspose.slides/notesslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)