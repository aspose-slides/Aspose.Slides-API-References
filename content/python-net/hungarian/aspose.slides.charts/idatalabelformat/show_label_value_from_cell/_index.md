---
title: show_label_value_from_cell property
second_title: Aspose.Slides Pythonhoz a .NET API Referenciában
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell tulajdonság
Az adott diagram adatcímke cellaérték megjelenítési viselkedését határozza meg. 
True megjeleníti a cella értékét. False elrejti.
Olvasás/írás **bool**.

### Megjegyzések
Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez
            tulajdonság lekéri vagy beállítja a ShowLabelValueFromCell tulajdonság alapértelmezett értékét az új adatcímkék
            számára a DataLabelCollection gyűjteményben.
            Ennek a tulajdonságnak az értékkel történő beállítása ugyanúgy beállítja ezt az értéket a ShowLabelValueFromCell tulajdonságra
            az összes adatcímkében a DataLabelCollection gyűjteményben
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" miatt
            minden DataLabels[i].ShowLabelValueFromCell egyenlő lesz a val értékkel).

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
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)