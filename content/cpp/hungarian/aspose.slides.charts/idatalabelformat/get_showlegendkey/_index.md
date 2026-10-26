---
title: get_ShowLegendKey()
second_title: Aspose.Slides C++ API referencia
description: Egy adott diagram adatcímkéjének jelmagyarázat kulcsának megjelenítési viselkedését ábrázolja. Igaz, ha az adatcímke jelmagyarázat kulcsa látható. Olvasás bool.
type: docs
weight: 92
url: /hu/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() metódus

Egy meghatározott diagram adatcímkéjének jelmagyarázat kulcsának megjelenítési viselkedését ábrázolja. Igaz, ha az adatcímke jelmagyarázat kulcsa látható. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanakkor ezt az értéket a ShowLegendKey tulajdonságra állítja az összes adatcímke esetén a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" hatására minden DataLabels[i].ShowLegendKey értéke megegyezik a val értékkel).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)