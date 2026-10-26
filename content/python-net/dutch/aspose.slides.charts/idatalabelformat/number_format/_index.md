---
title: number_format property
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format eigenschap
Stelt de notatiestring voor het DataLabels-object voor.
            Lezen/schrijven **str**.


### Opmerkingen

If parent of this DataLabelFormat object is a DataLabelCollection collection of gegevenslabels, then this
            eigenschap gets or sets the default value of the NumberFormat eigenschap for the new gegevens 
            labels in the DataLabelCollection collection.
            When this eigenschap is set with a value, that value is also set for the NumberFormat eigenschap for all gegevenslabels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### Definitie:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Zie ook
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)