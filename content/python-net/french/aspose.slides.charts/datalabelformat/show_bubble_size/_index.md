---
title: show_bubble_size property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size propriété
Représente le comportement d'affichage de la valeur de la taille de la bulle d'étiquette de données d'un graphique spécifié. 
True affiche la valeur de la taille de la bulle. False pour masquer.
Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection.  
Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowBubbleSize de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" entraîne que tous les DataLabels[i].ShowBubbleSize sont égaux à val).

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
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)