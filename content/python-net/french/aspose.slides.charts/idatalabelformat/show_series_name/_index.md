---
title: show_series_name property
second_title: Référence de l'API Aspose.Slides for Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## propriété show_series_name
Renvoie ou définit un Boolean indiquant le comportement d'affichage du nom de la série pour les étiquettes de données d'un graphique. 
            True pour afficher le nom de la série. False pour masquer.
            Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette
            propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles 
            étiquettes de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName 
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" provoque que 
            toutes les DataLabels[i].ShowSeriesName sont égales à val).

### Définition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Voir aussi
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)