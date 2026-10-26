---
title: set_ShowCategoryName()
second_title: Aspose.Slides C++-ra vonatkozó API hivatkozás
description: Egy meghatározott diagram adatcímkéjének kategórianév megjelenítési viselkedését jelöli. Igaz, ha a diagram adatcímkéinél megjelenik a kategórianév. Hamis, ha elrejtett. Írja bool.
type: docs
weight: 157
url: /hu/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) metódus


A megadott diagram adatcímkéjének kategórianév megjelenítési viselkedését jelöli. Igaz, ha a diagram adatcímkéinél megjelenik a kategórianév. Hamis, ha elrejtett. Írja **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Megjegyzések


Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímkégyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowCategoryName tulajdonság alapértelmezett értékét az új adatcímkékhez a [DataLabelCollection](../../datalabelcollection/) gyűjteményben.

Ennek a tulajdonságnak az értékkel való beállítása szintén az értéket a ShowCategoryName tulajdonságra állítja az összes adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" ami miatt minden DataLabels[i].ShowCategoryName értéke megegyezik a val értékkel). 



## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)