---
title: show_label_as_data_callout property
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout propriété
Détermine si l'étiquette de données du graphique spécifié sera affichée sous forme d'appel de données ou sous forme d'étiquette de données.
            
            Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette
            propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données
            dans la collection DataLabelCollection.
            Définir cette propriété avec valeur définit également cette valeur à la propriété ShowLabelAsDataCallout 
            pour toutes les étiquettes de données dans la collection DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" entraîne
            toutes les DataLabels[i].ShowLabelAsDataCallout sont égales à val).

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
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)