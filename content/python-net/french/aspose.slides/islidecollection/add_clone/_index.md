---
title: add_clone method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Ajoute une copie d'une slide spécifiée à la fin de la collection.

### Renvoie

Nouvelle slide.



```python
def add_clone(self, source_slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Slide à cloner. |

### Remarques

Lors du clonage d'une slide entre différentes présentations, le master de la slide peut également être cloné.
            Un registre interne est utilisé pour suivre les masters clonés automatiquement afin d'éviter la création de 
            plusieurs clones du même master slide.
            Le clonage manuel des masters slides ne sera ni empêché ni enregistré.
            Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** ou
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** pour cloner des slides,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** ou
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** pour cloner des layouts et
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** pour cloner des masters.


## add_clone(self, source_slide, section) {#islide-isection}
Ajoute une copie d'une slide spécifiée à la fin de la section spécifiée.

### Renvoie

Nouvelle slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Slide à cloner. |
| section | [`ISection`](/slides/python-net/fr/aspose.slides/isection) | Section pour une nouvelle slide. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Ajoute une copie d'une slide spécifiée à la fin de la collection.

### Renvoie

Nouvelle slide.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Slide à cloner. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Layout slide pour une nouvelle slide. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Ajoute une copie d'une slide source spécifiée à la fin de la collection.
            La mise en page appropriée sera sélectionnée automatiquement à partir du 
            master spécifié (la mise en page appropriée est celle qui a le même Type ou Name que 
            la mise en page de la slide source). S'il n'existe aucune mise en page appropriée alors
            la mise en page de la slide source sera clonée (si allowCloneMissingLayout 
            est vrai) ou PptxEditException sera levée (si allowCloneMissingLayout
            est faux).

### Renvoie

Nouvelle slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Slide à cloner. |
| dest_master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Master slide pour une nouvelle slide. |
| allow_clone_missing_layout | **bool** | Si aucune mise en page appropriée n'existe dans le master spécifié alors la mise en page de la <br/><br/>            slide source sera clonée (si allowCloneMissingLayout est vrai) ou <br/><br/>            PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée s'il n'existe aucune mise en page appropriée dans le master spécifié et <br/>            allowCloneMissingLayout est faux. |



### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* classe [`ISection`](/slides/python-net/fr/aspose.slides/isection)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`ISlideCollection`](/slides/python-net/fr/aspose.slides/islidecollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)