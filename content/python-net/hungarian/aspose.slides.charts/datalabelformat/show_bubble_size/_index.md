---
title: show_bubble_size property
second_title: Aspose.Slides for Python a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size tulajdonság
Egy meghatározott diagram adatcímke buborékméret-érték megjelenítési viselkedését képviseli.  
True megjeleníti a buborékméret értékét. False elrejti.  
Olvasás/írás **bool**.

### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkékben a ShowBubbleSize tulajdonság alapértelmezett értékét a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékkel való beállítása ugyanígy beállítja ezt az értéket a ShowBubbleSize tulajdonságra az összes adatcímkénál a DataLabelCollection gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" hatására minden DataLabels[i].ShowBubbleSize egyenlő lesz a val értékkel).

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
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)