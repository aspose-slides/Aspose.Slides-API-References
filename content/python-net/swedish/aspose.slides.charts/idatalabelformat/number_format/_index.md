---
title: number_format property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format egenskap
Representerar formatsträngen för DataLabels-objektet.
            Läs/skriva **str**.


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, så får den här egenskapen eller sätter standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen.
När denna egenskap sätts med ett värde, sätts samma värde också för NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" gör att alla DataLabels[i].NumberFormat blir lika med val).

### Definition:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Se även
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)