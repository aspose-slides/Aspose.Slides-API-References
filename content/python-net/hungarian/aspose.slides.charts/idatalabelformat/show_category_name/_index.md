---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name tulajdonság
Egy adott diagram adatcímke kategórianév megjelenítési viselkedését reprezentálja.
Igaz, ha megjeleníti a kategórianévét az adatcímkéknek egy diagramon. Hamis, ha elrejti.
Olvasás/írás **bool**.

### Megjegyzés

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowCategoryName tulajdonság alapértelmezett értékét az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowCategoryName tulajdonságra minden adatcímkénél a DataLabelCollection gyűjteményben (például "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" hatására minden DataLabels[i].ShowCategoryName egyenlő lesz a val értékkel).

### Definíció:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Lásd még
* osztály [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)