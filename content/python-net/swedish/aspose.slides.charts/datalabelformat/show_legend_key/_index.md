---
title: show_legend_key property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key egenskap
Representerar ett specificerat diagram datamärkes legendnyckels visningsbeteende.
True om legendnyckeln för datamärket är synlig.
Läsa/skriva **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, så får eller sätter den här egenskapen standardvärdet för ShowLegendKey egenskapen för de nya datamärkena i DataLabelCollection-samlingen.
Att sätta denna egenskap med ett värde sätter också detta värde till ShowLegendKey egenskapen för alla datamärken i DataLabelCollection-samlingen
(dvs. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" orsakar att alla DataLabels[i].ShowLegendKey är lika med val).

### Definition:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Se även
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)