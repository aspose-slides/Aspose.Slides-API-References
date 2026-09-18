---
title: show_category_name property
second_title: Aspose.Slides for Python .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name tulajdonság
Egy megadott diagram adatcímkéjeinek kategórianév megjelenítési viselkedését reprezentálja.  
True a kategórianév megjelenítéséhez a diagram adatcímkéin. False a elrejtéshez.  
Olvasás/írás **bool**.

### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a
tulajdonság beállítja vagy lekérdezi az új adatcímkékre a ShowCategoryName tulajdonság alapértelmezett értékét a DataLabelCollection gyűjteményben.  
Ennek a tulajdonságnak az érték beállítása ugyanakkor a ShowCategoryName tulajdonságot is beállítja az összes adatcímkére a DataLabelCollection gyűjteményben
(pl. `DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;` miatt minden `DataLabels[i].ShowCategoryName` egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### See Also
* osztály [`DataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)