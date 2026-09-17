---
title: show_category_name property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name propriété
Représente le comportement d'affichage du nom de catégorie des étiquettes de données d'un graphique spécifié.
True pour afficher le nom de catégorie des étiquettes de données sur un graphique. False pour masquer.
Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données de la collection DataLabelCollection (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" entraîne que toutes les DataLabels[i].ShowCategoryName sont égales à val).

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
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)