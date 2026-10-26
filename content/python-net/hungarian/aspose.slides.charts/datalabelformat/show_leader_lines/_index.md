---
title: show_leader_lines property
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines tulajdonság
Egy megadott diagram adatcímke vezetővonalainak megjelenítési viselkedését reprezentálja. 
True megjeleníti a vezetővonalakat. False elrejti.
Olvasás/írás **bool**.


### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLeaderLines tulajdonság alapértelmezett értékét az új adatcímkék számára a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowLeaderLines tulajdonságra az összes adatcímkénél a DataLabelCollection gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" hatására minden DataLabels[i].ShowLeaderLines értéke megegyezik a val értékkel).


### Definíció:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### Lásd még
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)