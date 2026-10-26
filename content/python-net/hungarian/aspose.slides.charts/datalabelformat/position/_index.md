---
title: position property
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## pozíció tulajdonság
A data label pozícióját jelöli.
            Olvasás/írás [`LegendDataLabelPosition`](/slides/python-net/hu/aspose.slides.charts/legenddatalabelposition).


### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkékhez a Position tulajdonság alapértelmezett értékét a DataLabelCollection gyűjteményben.
            A DataLabel objektumok pozícióját jelöli.
            Ennek a tulajdonságnak az értékével beállítva, a Position tulajdonság értéke is be lesz állítva az összes adatcímkére a DataLabelCollection gyűjteményben
            (azaz "DataLabels.DefaultDataLabelFormat.Position = val;" minden DataLabels[i].Position értéke a val lesz).

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
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* enumeráció [`LegendDataLabelPosition`](/slides/python-net/hu/aspose.slides.charts/legenddatalabelposition)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)