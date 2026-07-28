---
title: get_ShowValue()
second_title: Aspose.Slides C++ API hivatkozás
description: Egy adott diagram adatcímkéjének százalékos értékkijelzés viselkedését írja le. A true megjeleníti a százalékos értéket. A false elrejti. Olvasható bool.
type: docs
weight: 118
url: /hu/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() metódus


Egy adott diagram adatcímkéjének százalékos értékkijelzés viselkedését írja le. A true megjeleníti a százalékos értéket. A false elrejti. Olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## Megjegyzések


Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowValue tulajdonság alapértelmezett értékét az új adatcímkékhez a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowValue tulajdonságra az összes adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" minden DataLabels[i].ShowValue értékét a val-ra állítja).  



## Lásd még

* Osztály [IDataLabelFormat](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)