---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source egenskap
Läs/skriv **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken så får eller sätter denna egenskap standardvärdet för IsNumberFormatLinkedToSource-egenskapen för de nya datamärkena i DataLabelCollection-samlingen.
            Sätt denna egenskap med ett värde sätter också detta värde till IsNumberFormatLinkedToSource-egenskapen för alla datamärken i DataLabelCollection-samlingen
            (i.e. "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" orsakar att alla DataLabels[i].IsNumberFormatLinkedToSource är lika med val).

### Definition:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Se också
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)