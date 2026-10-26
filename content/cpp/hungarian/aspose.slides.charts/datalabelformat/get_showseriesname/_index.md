---
title: get_ShowSeriesName()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy Boolean értéket, amely jelzi a sorozatnév megjelenítési viselkedését a diagram adatcímkéken. True a sorozatnév megjelenítéséhez. False a rejtéshez. Olvasás bool.
type: docs
weight: 170
url: /hu/aspose.slides.charts/datalabelformat/get_showseriesname/
---
## DataLabelFormat::get_ShowSeriesName() metódus

Visszaad egy Boolean értéket, amely jelzi a sorozatnév megjelenítési viselkedését a diagram adatcímkéin. True a sorozatnév megjelenítéséhez. False a rejtéshez. Olvasás **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowSeriesName() override
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowSeriesName tulajdonság alapértelmezett értékét az új adatcímkékre a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowSeriesName tulajdonságra az összes adatcímkénél a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" miatt minden DataLabels[i].ShowSeriesName egyenlő lesz a val értékkel).

## Lásd még

* Osztály [DataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)