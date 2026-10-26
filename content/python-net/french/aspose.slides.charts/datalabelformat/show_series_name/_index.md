---
title: show_series_name property
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name propriété
Renvoie ou définit un booléen pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données d'un graphique. 
            True pour afficher le nom de la série. False pour masquer.
            Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowSeriesName de toutes les étiquettes de données dans la collection DataLabelCollection
            (c'est à dire "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" entraîne que toutes les DataLabels[i].ShowSeriesName sont égales à val).

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
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)