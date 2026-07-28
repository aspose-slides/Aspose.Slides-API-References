---
title: set_ShowLabelAsDataCallout()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a megadott diagram adatcímkéje adat hívóként vagy adatcímkeként jelenik meg.
type: docs
weight: 287
url: /hu/aspose.slides.charts/idatalabelformat/set_showlabelasdatacallout/
---
## IDataLabelFormat::set_ShowLabelAsDataCallout(bool) metódus

Meghatározza, hogy a megadott diagram adatcímkéje adat hívóként vagy adatcímkeként jelenik meg.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelAsDataCallout(bool value)=0
```

## Megjegyzés

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekérdezi vagy beállítja a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságban az összes adatcímkénél a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz \"DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;\" hatással van, hogy minden DataLabels[i].ShowLabelAsDataCallout egyenlő legyen a val értékkel).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)