---
title: show_legend_key property
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozással
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key tulajdonság
Képviseli egy megadott diagram adatcímke legenda kulcs megjelenítési viselkedését.  
True, ha az adatcímke legenda kulcs látható.  
Olvasás/írás **bool**.


### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a
tulajdonság beállítja vagy visszaadja a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkékhez a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowLegendKey tulajdonságra
az összes adatcímkénél a DataLabelCollection gyűjteményben
(pl. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" hatására
az összes DataLabels[i].ShowLegendKey egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### Lásd még
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)