---
title: set_Separator()
second_title: Aspose.Slides C++ API referencia
description: "Beállít vagy visszaad egy Variant értéket, amely a diagram adatcímkéinél használt elválasztót reprezentál. Írja System::String."
type: docs
weight: 339
url: /hu/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) metódus

Beállít vagy visszaad egy Variant értéket, amely a diagram adatcímkéinél használt elválasztót reprezentál. Írja [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Megjegyzés

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri az új adatcímkék Separator tulajdonságának alapértelmezett értékét a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a Separator tulajdonságra az összes adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.Separator = val;" okozza, hogy minden DataLabels[i].Separator értéke megegyezzen a val-vel).

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IDataLabelFormat](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)