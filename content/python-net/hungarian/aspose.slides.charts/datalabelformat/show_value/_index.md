---
title: show_value property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value tulajdonság
Egy megadott diagram adatcímkéjének százalékérték megjelenítési viselkedését írja le.
True megjeleníti a százalékértéket. False elrejti.
Olvasás/írás **bool**.

### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék ShowValue tulajdonságának alapértelmezett értékét a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyancsak beállítja ezt az értéket a ShowValue tulajdonságnak minden adatcímkére a DataLabelCollection gyűjteményben (azaz a "DataLabels.DefaultDataLabelFormat.ShowValue = val;" miatt minden DataLabels[i].ShowValue egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Lásd még
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)