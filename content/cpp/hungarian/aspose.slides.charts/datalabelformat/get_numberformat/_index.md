---
title: get_NumberFormat()
second_title: Aspose.Slides C++ API referenciája
description: "A DataLabels objektum formátumkarakterláncát reprezentálja. Olvassa el a System::String-et."
type: docs
weight: 27
url: /hu/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metódus


A formátumkarakterláncot képviseli a DataLabels objektum számára. Olvassa el [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Megjegyzések



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Ha ennek a [DataLabelFormat](../) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a NumberFormat tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Amikor ez a tulajdonság értékkel van beállítva, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra az összes adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" minden DataLabels[i].NumberFormat értékét a val-ra állítja).  



## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [DataLabelFormat](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)