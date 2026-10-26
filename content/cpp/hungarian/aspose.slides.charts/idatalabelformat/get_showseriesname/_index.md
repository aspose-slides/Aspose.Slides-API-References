---
title: get_ShowSeriesName()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy Boolean értéket, amely a diagram adatcímkéinek sorozatnév megjelenítési viselkedését jelzi. True a sorozatnév megjelenítéséhez. False a rejtéshez. Olvasás bool.
type: docs
weight: 170
url: /hu/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() metódus

Visszaad egy Boolean értéket, amely a diagram adatcímkéinek sorozatnév megjelenítési viselkedését jelzi. True a sorozatnév megjelenítéséhez. False a rejtéshez. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowSeriesName tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén ezt az értéket állítja be a ShowSeriesName tulajdonságra az összes adatcímke esetén a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" cause to all DataLabels[i].ShowSeriesName is equal to val). 

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)