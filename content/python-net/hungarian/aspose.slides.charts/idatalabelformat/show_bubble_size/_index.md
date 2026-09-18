---
title: show_bubble_size property
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size tulajdonság
Képviseli egy megadott diagram adatcímke buborékméret-értékének megjelenítési viselkedését. 
True megjeleníti a buborékméret-értéket. False elrejti.
Olvasás/írás **bool**.

### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkegyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék alapértelmezett ShowBubbleSize tulajdonságának értékét a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékkel való beállítása azt is beállítja a ShowBubbleSize tulajdonságban az összes adatcímke esetében a DataLabelCollection gyűjteményben (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" miatt minden DataLabels[i].ShowBubbleSize egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)