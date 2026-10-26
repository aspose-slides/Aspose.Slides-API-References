---
title: separator property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator-egenskap
Ställer in eller returnerar en Variant som representerar separatorn som används för dataetiketterna i ett diagram.
Läs/skriv **str**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får den här egenskapen eller sätter standardvärdet för Separator-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen.
Att sätta denna egenskap med ett värde sätter även detta värde till Separator-egenskapen för alla dataetiketter i DataLabelCollection-samlingen
(t.ex. "DataLabels.DefaultDataLabelFormat.Separator = val;" gör att alla DataLabels[i].Separator är lika med val).

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
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)