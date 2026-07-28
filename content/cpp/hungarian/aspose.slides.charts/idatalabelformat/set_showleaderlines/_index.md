---
title: set_ShowLeaderLines()
second_title: Aspose.Slides a C++ API referencia
description: Egy megadott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését reprezentálja. Az igaz érték megjeleníti a vezetővonalakat, a hamis érték elrejti őket. bool típusú értéket ír.
type: docs
weight: 261
url: /hu/aspose.slides.charts/idatalabelformat/set_showleaderlines/
---
## IDataLabelFormat::set_ShowLeaderLines(bool) metódus

Egy adott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését írja le. Az igaz érték megjeleníti a vezetővonalakat. A hamis érték elrejti őket. Írja **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLeaderLines(bool value)=0
```

## Megjegyzés

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a ShowLeaderLines tulajdonság alapértelmezett értékét az új adatcímkékhez a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowLeaderLines tulajdonságra az összes adatcímkében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" minden DataLabels[i].ShowLeaderLines értéke ezzel egyenlő lesz).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)