---
title: add_clone method
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Ajoute une copie d’une diapositive spécifiée à la fin de la collection.

### Valeur de retour

Nouvelle diapositive.



```python
def add_clone(self, source_slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |

### Remarques

Lors du clonage d’une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné.  
Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’empêcher la création de plusieurs clones du même maître de diapositive.  
Le clonage manuel des maîtres de diapositives ne sera ni empêché ni enregistré.  
Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** ou  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** pour cloner des diapositives,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** ou  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** pour cloner des dispositions et  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** pour cloner des maîtres.



## add_clone(self, source_slide, section) {#islide-isection}
Ajoute une copie d’une diapositive spécifiée à la fin de la section spécifiée.

### Valeur de retour

Nouvelle diapositive.



```python
def add_clone(self, source_slide, section):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| section | [`ISection`](/slides/python-net/fr/aspose.slides/isection) | Section pour la nouvelle diapositive. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Ajoute une copie d’une diapositive spécifiée à la fin de la collection.

### Valeur de retour

Nouvelle diapositive.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Disposition de diapositive pour la nouvelle diapositive. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Ajoute une copie d’une diapositive source spécifiée à la fin de la collection.  
La disposition appropriée sera sélectionnée automatiquement à partir du maître spécifié (la disposition appropriée est celle ayant le même Type ou le même Nom que la disposition de la diapositive source).  
S’il n’existe aucune disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux).

### Valeur de retour

Nouvelle diapositive.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| dest_master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Maître de diapositive pour la nouvelle diapositive. |
| allow_clone_missing_layout | **bool** | S’il n’existe aucune disposition appropriée dans le maître spécifié, alors la disposition de la <br/><br/>            diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou <br/><br/>            PptxEditException sera levée (si allowCloneMissingLayout est false). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée s’il n’existe aucune disposition appropriée dans le maître spécifié et <br/>            allowCloneMissingLayout est false. |



### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* classe [`ISection`](/slides/python-net/fr/aspose.slides/isection)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* classe [`SlideCollection`](/slides/python-net/fr/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)