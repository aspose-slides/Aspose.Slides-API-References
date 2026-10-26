---
title: set_NumberFormat()
second_title: Aspose.Slides C++ API hivatkozás
description: "Representálja a DataLabels objektum formátumkarakterláncát. Írja System::String."
type: docs
weight: 40
url: /hu/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metódus


A DataLabels objektum formátumkarakterláncát reprezentálja. Írja [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Megjegyzések



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekérdezi vagy beállítja a NumberFormat tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Amikor ez a tulajdonság egy értékkel van beállítva, az az érték szintén beállításra kerül a NumberFormat tulajdonságra az összes adatcímke esetében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (például a "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" miatt minden DataLabels[i].NumberFormat értéke megegyezik a val értékkel). 
## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IDataLabelFormat](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)