---
title: separator property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator egenskap
Ställer in eller returnerar en Variant som representerar separatorn som används för datamärkningarna i ett diagram.
            Läs/skriv **str**.


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, så får denna egenskap eller sätter standardvärdet för Separator-egenskapen för de nya datamärkningarna i DataLabelCollection-samlingen.
            Sätt denna egenskap med ett värde sätter också detta värde till Separator-egenskapen för alla datamärkningar i DataLabelCollection-samlingen
            (t.ex. "DataLabels.DefaultDataLabelFormat.Separator = val;" vilket gör att alla DataLabels[i].Separator blir lika med val).

### Definition:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Se också
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)