---
title: get_NumberFormat()
second_title: Aspose.Slides för C++ API-referens
description: "Representerar formatsträngen för DataLabels-objektet. Läs System::String."
type: docs
weight: 27
url: /sv/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() metod

Representerar formatsträngen för DataLabels-objektet. Läs [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Anmärkningar

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```


Om föräldern till detta [DataLabelFormat](../../datalabelformat/)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av dataetiketter, så får eller sätter den här egenskapen standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i [DataLabelCollection](../../datalabelcollection/)-samlingen. När den här egenskapen sätts med ett värde, sätts samma värde också för NumberFormat-egenskapen för alla dataetiketter i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" får alla DataLabels[i].NumberFormat att bli lika med val). 

## Se även

* Klass [String](../../../system/string/)
* Klass [IDataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)