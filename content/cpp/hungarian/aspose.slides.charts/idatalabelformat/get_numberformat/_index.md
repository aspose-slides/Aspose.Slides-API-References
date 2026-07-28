---
title: get_NumberFormat()
second_title: Aspose.Slides C++ API referencia
description: "A DataLabels objektum formátumkarakterláncát reprezentálja. Olvassa el a System::String-et."
type: docs
weight: 27
url: /hu/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() metódus


A DataLabels objektum formátumkarakterláncát reprezentálja. Olvassa el [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Megjegyzések



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a NumberFormat tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ha ez a tulajdonság értékkel van beállítva, akkor az érték ugyanúgy beállításra kerül a NumberFormat tulajdonság minden adatcímkéjére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" minden DataLabels[i].NumberFormat értéke megegyezik a val értékkel). 
## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)