---
title: show_label_as_data_callout property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout propriété
Détermine si l'étiquette de données du graphique spécifié sera affichée comme appel de données ou comme étiquette de données.

            Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette
            propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données 
            dans la collection DataLabelCollection.
            Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout 
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" entraîne 
            que tous DataLabels[i].ShowLabelAsDataCallout sont égaux à val).

### Définition:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)