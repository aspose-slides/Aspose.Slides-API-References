---
title: show_percentage property
second_title: Aspose.Slides for Python a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage tulajdonság
Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését írja le.  
A True megjeleníti a százalékos értéket. A False elrejti.  
Olvasás/írás **bool**.

### Megjegyzések

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowPercentage property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowPercentage property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" cause to 
            all DataLabels[i].ShowPercentage is equal to val).

### Definíció:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)