---
title: show_percentage property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage propriété
Représente le comportement d'affichage de la valeur de pourcentage d'un graphique spécifié.
True affiche la valeur du pourcentage. False pour masquer.
Lecture/écriture **bool**.

### Remarques
Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette
            propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles données 
            étiquettes dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage 
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" provoque que 
            toutes les DataLabels[i].ShowPercentage sont égales à val).

### Définition:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Voir aussi
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)