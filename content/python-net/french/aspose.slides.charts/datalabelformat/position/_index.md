---
title: position property
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position propriété
Représente la position du DataLabel.
Lecture/écriture [`LegendDataLabelPosition`](/slides/python-net/fr/aspose.slides.charts/legenddatalabelposition).

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection de libellés de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouveaux libellés de données dans la collection DataLabelCollection.
Représente la position pour les objets DataLabel.
Définir cette propriété avec une valeur définit également cette valeur à la propriété Position pour tous les libellés de données dans la collection DataLabelCollection
(c'est-à-dire "DataLabels.DefaultDataLabelFormat.Position = val;" entraîne que tous les DataLabels[i].Position sont égaux à val).

### Définition:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* énumération [`LegendDataLabelPosition`](/slides/python-net/fr/aspose.slides.charts/legenddatalabelposition)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)