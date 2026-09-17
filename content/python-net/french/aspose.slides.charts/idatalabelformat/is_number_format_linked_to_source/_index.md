---
title: is_number_format_linked_to_source property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source propriété
Lecture/écriture **bool**.

### Remarques

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles données 
            labels in the DataLabelCollection collection.
            Définir cette propriété avec value also sets this value to the IsNumberFormatLinkedToSource property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" cause to 
            all DataLabels[i].IsNumberFormatLinkedToSource is equal to val).

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
* classe [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)