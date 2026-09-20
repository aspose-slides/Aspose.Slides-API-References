---
title: show_label_as_data_callout property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout egenskap
Bestämmer om den specificerade diagrammets datamärkning ska visas som dataanrop eller som datamärkning.

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, får eller anger denna egenskap standardvärdet för ShowLabelAsDataCallout-egenskapen för de nya datamärkena i DataLabelCollection-samlingen.

Att sätta denna egenskap med ett värde sätter också detta värde på ShowLabelAsDataCallout-egenskapen för alla datamärken i DataLabelCollection-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" gör att alla DataLabels[i].ShowLabelAsDataCallout blir lika med val).

### Definition:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### Se även
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)