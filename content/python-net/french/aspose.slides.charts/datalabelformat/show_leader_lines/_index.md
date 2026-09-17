---
title: show_leader_lines property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines propriété
Représente le comportement d'affichage des lignes de repère des étiquettes de données d'un graphique spécifié.
            True affiche les lignes de repère. False pour les masquer.
            Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLeaderLines de toutes les étiquettes de données de la collection DataLabelCollection
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" entraîne que tous les DataLabels[i].ShowLeaderLines sont égaux à val).

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
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)