---
title: show_percentage property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage egenskap
Representerar ett specificerat diagrammets dataetikettprocentvärdesvisningsbeteende. 
True visar procentvärdet. False för att dölja.
Läs/skriv **bool**.

### Anmärkningar
Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så
egenskapen får eller sätter standardvärdet för ShowPercentage-egenskapen för de nya data
etiketterna i DataLabelCollection-samlingen.
Att sätta denna egenskap med ett värde sätter också detta värde till ShowPercentage-egenskapen
för alla dataetiketter i DataLabelCollection-samlingen
(dvs. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" orsakar att
alla DataLabels[i].ShowPercentage är lika med val).

### Definition:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Se även
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)