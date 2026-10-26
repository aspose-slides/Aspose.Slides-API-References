---
title: separator property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## szeparátor tulajdonság
Beállít vagy visszaad egy Variant értéket, amely a diagram adatcímkéinél használt elválasztót jelöli.
            Olvasás/írás **str**.

### Megjegyzés

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Separator property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the Separator property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to 
            all DataLabels[i].Separator is equal to val).

### Definíció:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Lásd még
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)