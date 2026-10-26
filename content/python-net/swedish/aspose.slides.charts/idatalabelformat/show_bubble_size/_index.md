---
title: show_bubble_size property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size egenskap
Representerar ett specificerat diagrammets datalabels bubbla storleksvärdesvisningsbeteende. 
True visar bubbelstorleksvärdet. False döljer det. 
Läs/skriv **bool**.

### Anmärkningar
Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datalabels, så får den här egenskapen eller sätter standardvärdet för ShowBubbleSize-egenskapen för de nya datalabels i DataLabelCollection-samlingen. 
Sätter du denna egenskap med ett värde sätter du också detta värde till ShowBubbleSize-egenskapen för alla datalabels i DataLabelCollection-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" gör att alla DataLabels[i].ShowBubbleSize är lika med val).

### Definition:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Se även
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)