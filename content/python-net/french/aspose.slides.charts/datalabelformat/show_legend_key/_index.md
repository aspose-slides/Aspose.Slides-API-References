---
title: show_legend_key property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key propriété
Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. 
            True si la clé de légende de l'étiquette de données est visible.
            Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette
            propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles 
            étiquettes de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLegendKey 
            de toutes les étiquettes de données dans la collection DataLabelCollection
            (c'est-a-dire "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" entraîne que 
            toutes les DataLabels[i].ShowLegendKey sont égales à val).

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
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)