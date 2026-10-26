---
title: get_Separator()
second_title: Aspose.Slides C++ API Referencia
description: "Beállít vagy visszaad egy Variant típust, amely a diagram adatcímkéjén használt elválasztót képviseli. Olvassa el a System::String-et."
type: docs
weight: 326
url: /hu/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() metódus

Beállít vagy visszaad egy Variant típust, amely a diagram adatcímkéken használt elválasztót képviseli. Olvasd [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Megjegyzések

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság a [DataLabelCollection](../../datalabelcollection/) gyűjteményben létrejövő új adatcímkék Separator tulajdonságának alapértelmezett értékét adja vissza vagy állítja be. Ennek a tulajdonságnak az értékkel való beállítása ugyancsak beállítja a Separator értékét az összes adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.Separator = val;" miatt minden DataLabels[i].Separator egyenlő lesz a val értékkel). 

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)