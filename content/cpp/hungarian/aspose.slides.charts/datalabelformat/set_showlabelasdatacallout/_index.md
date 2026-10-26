---
title: set_ShowLabelAsDataCallout()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza, hogy a megadott diagram adatcímkéje adat-kihívásként vagy adatcímke-ként jelenjen-e meg.
type: docs
weight: 313
url: /hu/aspose.slides.charts/datalabelformat/set_showlabelasdatacallout/
---
## DataLabelFormat::set_ShowLabelAsDataCallout(bool) metódus

Meghatározza, hogy a megadott diagram adatcímkéje adat-kihívásként vagy adatcímkéként jelenik-e meg.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowLabelAsDataCallout(bool value) override
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. A tulajdonság értékének beállítása ezzel egyidejűleg beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságra az összes adatcímke esetében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" miatt minden DataLabels[i].ShowLabelAsDataCallout egyenlő lesz a val értékkel).

## Lásd még

* Osztály [DataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)