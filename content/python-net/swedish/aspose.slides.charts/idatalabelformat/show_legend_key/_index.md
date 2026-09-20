---
title: show_legend_key property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key egenskap
Representerar beteendet för visning av legendnyckeln för en specificerad diagramdatasetikett. 
            Sant om legendnyckeln för datamärket är synlig.
            Läs/skriv **bool**.


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärkningar, så
            egenskap får eller sätter standardvärdet för ShowLegendKey-egenskapen för de nya datamärkningarna 
            i DataLabelCollection-samlingen.
            Att sätta denna egenskap till ett värde sätter också detta värde på ShowLegendKey-egenskapen 
            för alla datamärkningar i DataLabelCollection-samlingen
            (t.ex. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" gör att 
            alla DataLabels[i].ShowLegendKey är lika med val).

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
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)