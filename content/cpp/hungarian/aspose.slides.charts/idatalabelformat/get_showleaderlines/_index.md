---
title: get_ShowLeaderLines()
second_title: Aspose.Slides C++ API referencia
description: Egy adott diagram adatcímke vezetővonalainak megjelenítési viselkedését képviseli. True megjeleníti a vezetővonalakat. False elrejti. Olvasás bool.
type: docs
weight: 248
url: /hu/aspose.slides.charts/idatalabelformat/get_showleaderlines/
---
## IDataLabelFormat::get_ShowLeaderLines() metódus


Egy meghatározott diagram adatcímke vezetővonalainak megjelenítési viselkedését képviseli. True megjeleníti a vezetővonalakat. False elrejti. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLeaderLines()=0
```

## Megjegyzés


Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLeaderLines tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLeaderLines tulajdonságra az összes adatcímkében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" miatt minden DataLabels[i].ShowLeaderLines egyenlő lesz a val értékkel). 
## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)