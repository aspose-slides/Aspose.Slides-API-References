---
title: position property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position Eigenschaft
Stellt die Position der Datenbeschriftung dar.
Lesen/Schreiben [`LegendDataLabelPosition`](/slides/python-net/de/aspose.slides.charts/legenddatalabelposition).

### Anmerkungen

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Position property for the new data 
            labels in the DataLabelCollection collection.
            Stellt die Position für die DataLabel-Objekte dar.
            Set this property with value also sets this value to the Position property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" cause to 
            all DataLabels[i].Position is equal to val).

### Definition:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Siehe auch
* Klasse [`DataLabelFormat`](/slides/python-net/de/aspose.slides.charts/datalabelformat)
* Aufzählung [`LegendDataLabelPosition`](/slides/python-net/de/aspose.slides.charts/legenddatalabelposition)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)