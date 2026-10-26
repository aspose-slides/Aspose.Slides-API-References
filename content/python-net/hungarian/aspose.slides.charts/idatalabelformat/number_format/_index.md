---
title: number_format property
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozáson keresztül
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format tulajdonság
A DataLabels objektum formátumkarakterláncát jelöli.
            Olvasás/írás **str**.


### Megjegyzések

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekérdezi vagy beállítja a NumberFormat tulajdonság alapértelmezett értékét az új adatcímkékhez a DataLabelCollection gyűjteményben.
            Amikor ez a tulajdonság értékkel van beállítva, az érték a NumberFormat tulajdonságnál is beállításra kerül az összes adatcímkére a DataLabelCollection gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" hatására minden DataLabels[i].NumberFormat értéke megegyezik a val értékkel).

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
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)