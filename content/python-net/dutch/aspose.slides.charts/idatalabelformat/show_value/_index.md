---
title: show_value property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value eigenschap
Stelt het weergavegedrag van de percentagewaarde van een opgegeven grafieklabel voor. 
            True toont de percentagewaarde. False om te verbergen.
            Lezen/schrijven **bool**.


### Opmerkingen

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            eigenschap gets or sets de defaultwaarde van de ShowValue eigenschap voor de nieuwe data 
            labels in de DataLabelCollection collection.
            Set this eigenschap with value also sets this value to the ShowValue eigenschap 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to 
            all DataLabels[i].ShowValue is equal to val).

### Definitie:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### Zie ook
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)