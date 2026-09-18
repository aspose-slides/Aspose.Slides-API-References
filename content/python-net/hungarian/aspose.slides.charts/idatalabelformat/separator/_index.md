---
title: separator property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator tulajdonság
Beállítja vagy visszaadja a Variant-et, amely a diagramon a adatcímkékhez használt separator-t képviseli.
Olvasás/írás **str**.

### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a Separator tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben.
Ezzel a tulajdonsággal beállított érték szintén beállítja ezt az értéket a Separator tulajdonságra a DataLabelCollection összes adatcímkéjében
(azaz "DataLabels.DefaultDataLabelFormat.Separator = val;" miatt minden DataLabels[i].Separator egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)