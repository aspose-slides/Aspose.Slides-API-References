---
title: set_NumberFormat()
second_title: Aspose.Slides C++ API referencia
description: "A DataLabels objektum formátum karakterláncát jelöli. Írja be a System::String-et."
type: docs
weight: 40
url: /hu/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) metódus


A DataLabels objektum formátum karakterláncát jelöli. Írja be a [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Megjegyzések



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Ha ennek a [DataLabelFormat](../) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az alapértelmezett értékét a NumberFormat tulajdonságnak az új adatcímkéknél a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Amikor ez a tulajdonság értékkel van beállítva, az az érték szintén beállításra kerül a NumberFormat tulajdonságra az összes adatcímkében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" minden DataLabels[i].NumberFormat értékét val-ra állítja).  



## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [DataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)