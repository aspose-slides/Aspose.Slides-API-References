---
title: show_label_as_data_callout property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout egenskap
Bestämmer om den specificerade diagrammets datalabel kommer att visas som dataanrop eller som datalabel.
            
            Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datalabel så
            egenskap hämtar eller sätter standardvärdet för ShowLabelAsDataCallout egenskapen för de nya datalabel
            i DataLabelCollection-samlingen.
            Sätt denna egenskap med värde sätter också detta värde till ShowLabelAsDataCallout egenskapen
            för alla datalabel i DataLabelCollection-samlingen
            (t.ex. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" orsakar att 
            alla DataLabels[i].ShowLabelAsDataCallout är lika med val).

### Definition:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```


### Se också
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)