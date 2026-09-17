---
title: show_category_name property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name propriété
Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié.
            True pour afficher le nom de catégorie des étiquettes de données sur un graphique. False pour masquer.
            Lecture/écriture **bool**.


### Remarques

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles données 
            étiquettes dans la collection DataLabelCollection.
            Définissez cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName 
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause à toutes DataLabels[i].ShowCategoryName est égal à val).

### Définition:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)