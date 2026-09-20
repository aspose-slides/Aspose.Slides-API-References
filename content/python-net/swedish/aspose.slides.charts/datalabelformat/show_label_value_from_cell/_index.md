---
title: show_label_value_from_cell property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell egenskap
Representerar ett specificerat diagrammets datamärkescellvärdesvisningsbeteende. 
            True visar cellvärdet. False för att dölja.
            Läs/skriv **bool**.


### Anmärkningar

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            egenskap får eller sätter standardvärdet för ShowLabelValueFromCell egenskapen för de nya data 
            labels in the DataLabelCollection collection.
            Att sätta denna egenskap med value also sets this value to the ShowLabelValueFromCell egenskap 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" orsakar att 
            all DataLabels[i].ShowLabelValueFromCell är lika med val).

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
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)