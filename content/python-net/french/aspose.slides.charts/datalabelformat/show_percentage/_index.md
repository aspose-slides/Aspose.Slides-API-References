---
title: show_percentage property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage propriété
Représente le comportement d'affichage de la valeur de pourcentage du libellé de données d'un graphique spécifié. 
            True affiche la valeur du pourcentage. False pour masquer.
            Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection de libellés de données alors cette
            propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouveaux libellés 
            de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage 
            pour tous les libellés de données dans la collection DataLabelCollection
            (c'est-a-dire "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" entraîne que 
            tous les DataLabels[i].ShowPercentage sont égaux à val).

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
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)