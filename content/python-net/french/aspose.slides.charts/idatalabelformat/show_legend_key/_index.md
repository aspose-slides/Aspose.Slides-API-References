---
title: show_legend_key property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key propriété
Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. 
            True si la clé de légende de l'étiquette de données est visible.
            Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données de la collection DataLabelCollection
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" entraîne que tous les DataLabels[i].ShowLegendKey sont égaux à val).

### Définition:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### Voir aussi
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)