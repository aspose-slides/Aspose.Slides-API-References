---
title: show_label_as_data_callout property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout tulajdonság
Meghatározza, hogy a megadott diagram adatcímkéje adat-hívásként vagy adatcímkeként jelenik meg.
            
            Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék számára a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét a DataLabelCollection gyűjteményben.
            Ennek a tulajdonságnak az értékkel való beállítása ugyancsak beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságra az összes adatcímkére a DataLabelCollection gyűjteményben
            (azaz "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" hatással van arra, hogy az összes DataLabels[i].ShowLabelAsDataCallout értéke megegyezzen a val értékkel).

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
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)