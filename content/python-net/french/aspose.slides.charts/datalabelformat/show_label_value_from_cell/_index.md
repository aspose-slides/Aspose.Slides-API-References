---
title: show_label_value_from_cell property
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell propriété
Représente le comportement d'affichage de la valeur de la cellule d'étiquette de données d'un graphique spécifié. 
            True affiche la valeur de la cellule. False pour masquer.
            Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection.  
Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" entraîne que tous les DataLabels[i].ShowLabelValueFromCell sont égaux à val).


### Définition:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)