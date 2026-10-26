---
title: number_format property
second_title: Aspose.Slides Python számára a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format tulajdonság
A DataLabels objektum formátum karakterláncát jelenti.
            Olvasás/írás **str**.


### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a
            tulajdonság beállítja vagy lekérdezi az új adatcímkék NumberFormat tulajdonságának alapértelmezett értékét a DataLabelCollection gyűjteményben.
            Amikor ez a tulajdonság értékkel van beállítva, akkor az érték szintén beállításra kerül a NumberFormat tulajdonságra minden adatcímkében a DataLabelCollection gyűjteményben
            (pl. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" minden DataLabels[i].NumberFormat értéke val lesz).

### Definíció:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Lásd még
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)