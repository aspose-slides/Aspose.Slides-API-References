---
title: add_clone method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

### Retour
Diapositive ajoutée.



```python
def add_clone(self, source_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive à cloner. |

### Remarques
Lors du clonage d’une mise en page entre différentes présentations, le maître de la mise en page peut également être cloné
            pour conserver le formatage source.
            Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de 
            clones multiples du même maître de diapositive.
            Le clonage manuel des diapositives maîtres ne sera ni empêché ni enregistré.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

### Retour
Diapositive ajoutée.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive à cloner. |
| dest_master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Diapositive maître pour la nouvelle mise en page. |

### Remarques
Une nouvelle mise en page sera liée au maître défini dans la présentation de destination.
            C’est donc l’équivalent d’un copier/coller avec l’option "Use Destination Theme" dans PowerPoint.



### Voir aussi
* classe [`IGlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/igloballayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)