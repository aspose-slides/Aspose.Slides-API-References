---
title: show_percentage property
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage tulajdonság
A megadott diagram adatcímkéjének százalékérték-megjelenítési viselkedését reprezentálja.  
True megjeleníti a százalékértéket. False elrejti.  
Olvasás/írás **bool**.

### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a property lekéri vagy beállítja az új adatcímkékhez a ShowPercentage property alapértelmezett értékét a DataLabelCollection gyűjteményben.  
Ezzel a property-vel történő beállítás értéke szintén beállítja ezt az értéket a ShowPercentage property-re a DataLabelCollection gyűjtemény összes adatcímkéjére (azaz "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" hatására minden DataLabels[i].ShowPercentage értéke megegyezik a val értékkel).

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
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)