---
title: show_value property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value egenskap
Representerar ett specificerat diagrammets datamärkningens procentvärdesvisningsbeteende. 
True visar procentvärdet. False döljer det.
Läs/skriv **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, så får eller sätter denna egenskap standardvärdet för ShowValue Property för de nya datamärkena i DataLabelCollection-samlingen. Att sätta denna egenskap med ett värde sätter också detta värde till ShowValue Property för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" gör att alla DataLabels[i].ShowValue är lika med val).

### Definition:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Se också
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)