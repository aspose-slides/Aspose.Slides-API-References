---
title: show_percentage property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage egenskap
Representerar ett specificerat diagrammets datalabels procentvärdesvisningsbeteende.
            True visar procentvärdet. False för att dölja.
            Läs/skriv **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datalabels så hämtar eller sätter denna
            egenskap standardvärdet för ShowPercentage-egenskapen för de nya datalabels i DataLabelCollection-samlingen.
            Sätt detta värde på egenskapen så sätts även detta värde på ShowPercentage-egenskapen
            för alla datalabels i DataLabelCollection-samlingen
            (t.ex. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" gör att
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
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)