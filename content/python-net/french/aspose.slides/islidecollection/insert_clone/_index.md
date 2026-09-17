---
title: insert_clone method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Insère une copie d’une diapositive spécifiée à la position indiquée de la collection.

### Retour

Diapositive insérée.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice de la nouvelle diapositive. |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |

### Remarques

Lors du clonage d’une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné.  
Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d’éviter la création de multiples clones du même maître de diapositive.  
Le clonage manuel des maîtres de diapositives ne sera ni empêché ni enregistré.  
Si vous avez besoin de davantage de contrôle sur le processus de clonage, utilisez  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** ou  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** pour cloner des diapositives et  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** pour cloner des maîtres.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Insère une copie d’une diapositive spécifiée à la position indiquée de la collection.

### Retour

Diapositive insérée.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice de la nouvelle diapositive. |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Disposition de la diapositive pour une nouvelle diapositive. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Insère une copie d’une diapositive source spécifiée à la position indiquée de la collection.  
La disposition appropriée sera sélectionnée automatiquement à partir du maître spécifié  
(la disposition appropriée est celle ayant le même Type ou le même Nom que la disposition de la diapositive source). Si aucune disposition appropriée n’existe,  
la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux).

### Retour

Diapositive insérée.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice de la nouvelle diapositive. |
| source_slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive à cloner. |
| dest_master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Maître de la diapositive pour une nouvelle diapositive. |
| allow_clone_missing_layout | **bool** | Si aucune disposition appropriée n'existe dans le maître spécifié alors la disposition de la <br/><br/>            diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou <br/><br/>            PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée s'il n'existe aucune disposition appropriée dans le maître spécifié et \n            allowCloneMissingLayout est faux. |



### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* classe [`ISlideCollection`](/slides/python-net/fr/aspose.slides/islidecollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)