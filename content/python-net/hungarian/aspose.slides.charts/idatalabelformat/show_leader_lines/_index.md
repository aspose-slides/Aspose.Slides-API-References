---
title: show_leader_lines property
second_title: Aspose.Slides Python számára .NET-en keresztül API-referenciaként
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines tulajdonság
Egy meghatározott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését reprezentálja. 
True megjeleníti a vezetővonalakat. False elrejti. 
Olvasás/írás **bool**.

### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekérdezi vagy beállítja a ShowLeaderLines tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowLeaderLines tulajdonságra az összes adatcímkére a DataLabelCollection gyűjteményben (például "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" minden DataLabels[i].ShowLeaderLines értékét egyenlővé teszi a val-vel).

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
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)