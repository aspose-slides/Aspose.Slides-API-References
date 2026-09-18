---
title: show_label_value_from_cell property
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell tulajdonság
Egy meghatározott diagram adatcímkéjének cellaérték-megjelenítési viselkedését reprezentálja. 
True megjeleníti a cellaértéket. False elrejti.
Olvasás/írás **bool**.


### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkéket tartalmazó gyűjtemény, akkor ez a tulajdonság lekérdezi vagy beállítja a ShowLabelValueFromCell tulajdonság alapértelmezett értékét az új adatcímkékhez a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLabelValueFromCell tulajdonságra is beállítja a DataLabelCollection gyűjteményben lévő összes adatcímkére  
(azaz "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" azt eredményezi, hogy minden DataLabels[i].ShowLabelValueFromCell egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Lásd még
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)