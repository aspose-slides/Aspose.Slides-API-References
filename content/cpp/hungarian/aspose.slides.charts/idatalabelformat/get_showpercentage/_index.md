---
title: get_ShowPercentage()
second_title: Aspose.Slides C++ API-referencia
description: Képviseli egy meghatározott diagram adatcímkéjének százalékos érték megjelenítésének viselkedését. Az igaz (True) megjeleníti a százalékos értéket. A hamis (False) elrejti. Olvasható bool.
type: docs
weight: 196
url: /hu/aspose.slides.charts/idatalabelformat/get_showpercentage/
---
## IDataLabelFormat::get_ShowPercentage() metódus

Az adott diagram adatcímkéjének százalékos értéke megjelenítésének viselkedése. Az igaz (True) megjeleníti a százalékos értéket. A hamis (False) elrejti. Olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowPercentage()=0
```

## Megjegyzés

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság a [DataLabelCollection](../../datalabelcollection/) gyűjtemény új adatcímkéinek a ShowPercentage tulajdonság alapértelmezett értékét adja vissza vagy állítja be. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a [DataLabelCollection](../../datalabelcollection/) gyűjtemény összes adatcímkéjének a ShowPercentage tulajdonságára (pl. \"DataLabels.DefaultDataLabelFormat.ShowPercentage = val;\" okozza, hogy minden DataLabels[i].ShowPercentage egyenlő legyen a val értékkel).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)