---
title: position property
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position tulajdonság
Represents the position of the data label.
            Olvasás/írás [`LegendDataLabelPosition`](/slides/python-net/hu/aspose.slides.charts/legenddatalabelposition).

### Megjegyzések
Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a Position tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben.
            Képviseli a position-t a DataLabel objektumok számára.
            Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a Position tulajdonságra az összes adatcímkére a DataLabelCollection gyűjteményben
            (azaz "DataLabels.DefaultDataLabelFormat.Position = val;" miatt minden DataLabels[i].Position egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* felsorolás [`LegendDataLabelPosition`](/slides/python-net/hu/aspose.slides.charts/legenddatalabelposition)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)