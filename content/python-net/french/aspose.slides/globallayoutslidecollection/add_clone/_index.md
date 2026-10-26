---
title: add_clone method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

### Returns

Diapositive ajoutée.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive à cloner. |

### Remarks

Lors du clonage d’une mise en page entre différentes présentations, le maître de la mise en page peut également être cloné afin de conserver le formatage d’origine. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’empêcher la création de plusieurs clones du même diapositive maître. Le clonage manuel des diapositives maîtres ne sera ni empêché ni enregistré.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Ajoute une copie d’une diapositive de mise en page spécifiée à la présentation.

### Returns

Diapositive ajoutée.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive à cloner. |
| dest_master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Diapositive maître pour une nouvelle mise en page. |

### Remarks

1) La nouvelle mise en page sera liée au maître défini dans la présentation de destination.  
   Ainsi, c’est l’analogue de copier/coller avec l’option « Utiliser le thème de destination » dans PowerPoint.  
2) L’analogue de cette méthode est la méthode **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** accessible via la propriété [`IMasterSlide.layout_slides`](/slides/python-net/fr/aspose.slides/imasterslide/layout_slides).



### See Also
* class [`GlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)