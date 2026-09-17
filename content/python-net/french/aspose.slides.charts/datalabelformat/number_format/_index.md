---
title: number_format property
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format propriété
Représente la chaîne de format pour l'objet DataLabels.
            Lecture/écriture **str**.


### Remarques

            Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
            Lorsque cette propriété est définie avec une valeur, cette valeur est également définie pour la propriété NumberFormat de toutes les étiquettes de données dans la collection DataLabelCollection (c.-à-d. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" provoque que tous les DataLabels[i].NumberFormat soient égaux à val).

### Définition:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)