---
title: is_number_format_linked_to_source property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source propriété
Lecture/écriture **bool**.

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection.
Définir cette propriété avec valeur définit également cette valeur pour la propriété IsNumberFormatLinkedToSource de toutes les étiquettes de données dans la collection DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" entraîne que toutes les DataLabels[i].IsNumberFormatLinkedToSource sont égales à val).

### Définition:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Voir aussi
* classe [`DataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)