---
title: show_value property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value propriété
Représente le comportement d'affichage de la valeur de pourcentage des étiquettes de données d'un graphique spécifié. 
            True affiche la valeur de pourcentage. False pour masquer.
            Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. 
            Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données dans la collection DataLabelCollection 
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to all DataLabels[i].ShowValue is equal to val).

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
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)