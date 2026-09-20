---
title: position property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## positionsegenskap
Representerar positionen för datamärket.
Läsa/skriva [`LegendDataLabelPosition`](/slides/python-net/sv/aspose.slides.charts/legenddatalabelposition).

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamärken, så får den här egenskapen eller sätter standardvärdet för Position-egenskapen för de nya datamärkena i DataLabelCollection-samlingen.  
Representerar positionen för DataLabel-objekten.  
Ställ in den här egenskapen med ett värde sätter även detta värde på Position-egenskapen för alla datamärken i DataLabelCollection-samlingen (t.ex. "DataLabels.DefaultDataLabelFormat.Position = val;" gör så att alla DataLabels[i].Position är lika med val).

### Definition:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Se även
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* enumeration [`LegendDataLabelPosition`](/slides/python-net/sv/aspose.slides.charts/legenddatalabelposition)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)