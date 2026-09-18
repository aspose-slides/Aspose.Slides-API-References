---
title: show_value property
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value tulajdonság
Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja.  
True megjeleníti a százalékos értéket. False elrejti.  
Olvasás/írás **bool**.


### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri az új adatcímkék alapértelmezett ShowValue Property értékét a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowValue Property-re minden adatcímkében a DataLabelCollection gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowValue = val;" miatt minden DataLabels[i].ShowValue egyenlő lesz a val értékkel).


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
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)