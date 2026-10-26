---
title: show_bubble_size property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size propriété
Représente le comportement d'affichage de la valeur de la taille des bulles d'étiquette de données d'un graphique spécifié. 
            True affiche la valeur de la taille des bulles. False pour masquer.
            Lecture/écriture **bool**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowBubbleSize de toutes les étiquettes de données dans la collection DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" cause to all DataLabels[i].ShowBubbleSize is equal to val).


### Définition:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### Voir aussi
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)