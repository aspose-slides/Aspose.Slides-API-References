---
title: get_Separator()
second_title: Aspose.Slides C++ API referenciája
description: "Beállítja vagy visszaadja azt a Variant-et, amely a diagram adatcímkéinél használt elválasztót képviseli. Olvassa el System::String."
type: docs
weight: 326
url: /hu/aspose.slides.charts/datalabelformat/get_separator/
---
## DataLabelFormat::get_Separator() metódus

Beállítja vagy visszaadja a Variant-et, amely a diagram adatcímkéinél használt elválasztót képviseli. Olvassa el [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_Separator() override
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a Separator tulajdonság alapértelmezett értékét az új adatcímkéknél a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanígy beállítja ezt az értéket a Separator tulajdonságra az összes adatcímkében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.Separator = val;" hatásával minden DataLabels[i].Separator egyenlő lesz a val értékkel).

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [DataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)