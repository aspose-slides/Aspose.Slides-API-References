---
title: show_series_name property
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name tulajdonság
Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
            True a sorozatnév megjelenítéséhez. False a elrejtéshez.
            Olvasás/írás **bool**.


### Megjegyzések
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            tulajdonság lekéri vagy beállítja a ShowSeriesName tulajdonság alapértelmezett értékét az új adatcímkék
            a DataLabelCollection gyűjteményben.
Set this property with value also sets this value to the ShowSeriesName property
            az összes adatcímkére a DataLabelCollection gyűjteményben
(például "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" hatására
            minden DataLabels[i].ShowSeriesName egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)