---
title: number_format property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format egenskap
Representerar formatsträngen för DataLabels-objektet.
            Läs/skriv **str**.



### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, då detta
            egenskapen får eller sätter standardvärdet för NumberFormat-egenskapen för den nya data 
            etiketter i DataLabelCollection-samlingen.
            När denna egenskap sätts med ett värde, sätts det värdet också för NumberFormat-egenskapen för alla dataetiketter i DataLabelCollection-samlingen
            (t.ex. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" orsakar att alla DataLabels[i].NumberFormat blir lika med val).

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
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)