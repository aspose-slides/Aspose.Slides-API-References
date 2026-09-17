---
title: separator property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## propriété separator
Définit ou renvoie un Variant représentant le separator utilisé pour les étiquettes de données sur un graphique.
            Lecture/écriture **str**.


### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur sur la propriété Separator pour toutes les étiquettes de données de la collection DataLabelCollection
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.Separator = val;" entraîne que tous les DataLabels[i].Separator sont égaux à val).

### Définition:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)