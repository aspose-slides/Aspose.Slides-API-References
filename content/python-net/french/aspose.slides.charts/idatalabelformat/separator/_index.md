---
title: separator property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## propriété du séparateur
Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique.
Lecture/écriture **str**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données de la collection DataLabelCollection.
Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données de la collection DataLabelCollection
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
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)