---
title: show_label_value_from_cell property
second_title: Aspose.Slides för Python via .NET API-referens
description:
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell egenskap
Representerar ett specificerat diagrammets dataetikettcellvärdes visningsbeteende. 
            True visar cellvärdet. False döljer det.
            Läs/skriv **bool**.


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så är detta
            egenskap hämtar eller sätter standardvärdet för ShowLabelValueFromCell-egenskapen för de nya data 
            etiketterna i DataLabelCollection-samlingen.
            Att sätta denna egenskap med ett värde sätter också detta värde till ShowLabelValueFromCell-egenskapen 
            för alla dataetiketter i DataLabelCollection-samlingen
            (t.ex. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" orsakar att 
            alla DataLabels[i].ShowLabelValueFromCell är lika med val).

### Definition:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Se även
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)