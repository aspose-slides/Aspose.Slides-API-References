---
title: set_ShowValue()
second_title: Aspose.Slides C++ API Referencia
description: Egy meghatározott diagram adatcímkéjének százalékos értékmegjelenítési viselkedését reprezentálja. True megjeleníti a százalékos értéket. False elrejti. Írja bool.
type: docs
weight: 131
url: /hu/aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) metódus

Egy meghatározott diagram adatcímkéjének százalékos értékmegjelenítési viselkedését reprezentálja. True esetén megjeleníti a százalékos értéket. False elrejti. Írja **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowValue tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén ezt az értéket állítja be a ShowValue tulajdonságnál minden adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowValue = val;" miatt minden DataLabels[i].ShowValue megegyezik a val értékkel).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)