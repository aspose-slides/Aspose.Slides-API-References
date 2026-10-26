---
title: insert_clone method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Insère une copie d’une diapositive spécifiée à la position indiquée de la collection.

### Returns

Diapositive insérée.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice de la nouvelle diapositive. |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |

### Remarks

Lorsque la diapositive est clonée entre différentes présentations, le maître de la diapositive peut également être cloné.
            Le registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de multiples clones du même maître de diapositive.
            Le clonage manuel des maîtres de diapositives ne sera ni empêché ni enregistré.
            Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** ou
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** pour cloner des diapositives et
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** pour cloner des maîtres.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Insère une copie d’une diapositive spécifiée à la position indiquée de la collection.

### Returns

Diapositive insérée.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice de la nouvelle diapositive. |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive de mise en page pour la nouvelle diapositive. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Insère une copie d’une diapositive source spécifiée à la position indiquée de la collection.
            La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié 
            (la mise en page appropriée est celle qui a le même Type ou le même Nom que 
            la mise en page de la diapositive source). S’il n’existe aucune mise en page appropriée alors
            la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout 
            est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout
            est faux).

### Returns

Diapositive insérée.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice de la nouvelle diapositive. |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| dest_master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Diapositive maître pour une nouvelle diapositive. |
| allow_clone_missing_layout | **bool** | S’il n’existe aucune mise en page appropriée dans le maître spécifié, alors la mise en page de la <br/><br/>            diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou <br/><br/>            une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée s’il n’existe aucune mise en page appropriée dans le maître spécifié et <br/>            allowCloneMissingLayout est faux. |



### See Also
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* classe [`SlideCollection`](/slides/python-net/fr/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)