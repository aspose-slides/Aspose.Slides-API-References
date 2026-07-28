---
title: get_ShowCategoryName()
second_title: Aspose.Slides C++ API Referencia
description: Egy megadott diagram adatcímke kategórianév megjelenítési viselkedését reprezentálja. True a diagram adatcímkéinek kategórianév megjelenítéséhez. False a rejtéshez. Olvas bool.
type: docs
weight: 144
url: /hu/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() metódus

Egy megadott diagram adatcímke kategórianév megjelenítési viselkedését reprezentálja. True a kategórianév megjelenítéséhez a diagram adatcímkéin. False a rejtéshez. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowCategoryName tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. A tulajdonság értékével való beállítás ugyanakkor ezt az értéket a ShowCategoryName tulajdonságra is alkalmazza a [DataLabelCollection](../../datalabelcollection/) gyűjtemény összes adatcímkéjére (pl. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" miatt minden DataLabels[i].ShowCategoryName egyenlő lesz a val értékkel).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)