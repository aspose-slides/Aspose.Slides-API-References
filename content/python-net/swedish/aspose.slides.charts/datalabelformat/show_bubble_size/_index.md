---
title: show_bubble_size property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size egenskap
Representerar ett specificerat diagramts datapunktetikett bubble size-värdesvisningsbeteende. 
            True visar bubble size-värdet. False för att dölja.
            Läs/skriv **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datapunktetiketter så får denna
            egenskap eller sätter standardvärdet för ShowBubbleSize-egenskapen för de nya datapunktetiketterna i DataLabelCollection-samlingen.
            Sätt detta värde så sätts även detta värde till ShowBubbleSize-egenskapen
            för alla datapunktetiketter i DataLabelCollection-samlingen
            (dvs. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" orsakar att 
            alla DataLabels[i].ShowBubbleSize är lika med val).

### Definition:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Se också
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)