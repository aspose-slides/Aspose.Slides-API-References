---
title: show_label_as_data_callout property
second_title: Aspose.Slides Python számára .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout tulajdonság
Meghatározza, hogy a megadott diagram adatcímkéje adatfelhívásként vagy adatcímkéként jelenik meg.

            Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez
            tulajdonság lekérdezi vagy beállítja a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét az új adat
            címkék számára a DataLabelCollection gyűjteményben.
            Ennek a tulajdonságnak az értékbeállítása szintén beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságra
            az összes adatcímkére a DataLabelCollection gyűjteményben
            (azaz "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" okozza, 
            minden DataLabels[i].ShowLabelAsDataCallout egyenlő legyen a val-val).

### Definíció:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)