---
title: position property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## positionsegenskap
Representerar positionen för dataetiketten.
            Läs/skriv [`LegendDataLabelPosition`](/slides/python-net/sv/aspose.slides.charts/legenddatalabelposition).


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter, får den här egenskapen eller sätter standardvärdet för Position property för de nya dataetiketterna i DataLabelCollection-samlingen.
Representerar positionen för DataLabel-objekten.
Ställ in denna egenskap med ett värde sätter också detta värde till Position property för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.Position = val;" vilket gör att alla DataLabels[i].Position är lika med val).

### Definition:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```


### Se också
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* enumeration [`LegendDataLabelPosition`](/slides/python-net/sv/aspose.slides.charts/legenddatalabelposition)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)