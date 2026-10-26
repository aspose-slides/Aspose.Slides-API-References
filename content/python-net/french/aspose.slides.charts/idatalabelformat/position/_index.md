---
title: position property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position propriété
Représente la position de l'étiquette de données.
            Lecture/écriture [`LegendDataLabelPosition`](/slides/python-net/fr/aspose.slides.charts/legenddatalabelposition).

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette
            propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles
            étiquettes dans la collection DataLabelCollection.
Représente la position des objets DataLabel.
Définir cette propriété avec une valeur définit également cette valeur à la propriété Position
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.Position = val;" entraîne
            que tous les DataLabels[i].Position sont égaux à val).

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
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* énumération [`LegendDataLabelPosition`](/slides/python-net/fr/aspose.slides.charts/legenddatalabelposition)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)