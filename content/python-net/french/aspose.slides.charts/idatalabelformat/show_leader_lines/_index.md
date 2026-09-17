---
title: show_leader_lines property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines propriété
Représente le comportement d’affichage des lignes de repère des étiquettes de données d’un graphique spécifié. 
            True affiche les lignes de repère. False pour les masquer.
            Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données alors cet
            propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles
            étiquettes dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLeaderLines 
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" provoque 
            que tous DataLabels[i].ShowLeaderLines sont égaux à val).

### Définition:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Voir aussi
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)