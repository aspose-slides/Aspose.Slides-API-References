---
title: show_value property
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value propriété
Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié.
True affiche la valeur en pourcentage. False pour masquer.
Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" entraîne que tous les DataLabels[i].ShowValue sont égaux à val).


### Définition:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### Voir aussi
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)