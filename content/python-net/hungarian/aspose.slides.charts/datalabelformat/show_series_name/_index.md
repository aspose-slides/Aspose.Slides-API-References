---
title: show_series_name property
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name tulajdonság
Visszaadja vagy beállítja a Boolean értéket, amely azt jelzi, hogyan jelenjen meg a sorozat neve a diagram adatcímkéin.  
True – a sorozat nevének megjelenítéséhez. False – elrejtéshez.  
Olvasás/írás **bool**.

### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék alapértelmezett ShowSeriesName tulajdonság értékét a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékével együtt beállítja ezt az értéket a ShowSeriesName tulajdonságra a DataLabelCollection összes adatcímkéjében (azaz "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" miatt minden DataLabels[i].ShowSeriesName egyenlő lesz a val értékkel).

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
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)