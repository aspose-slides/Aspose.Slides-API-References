---
title: set_NumberFormat()
second_title: Aspose.Slides för C++ API-referens
description: "Representerar formatsträngen för DataLabels-objektet. Skriv System::String."
type: docs
weight: 40
url: /sv/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) metod

Representerar formatsträngen för DataLabels-objektet. Skriv [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Anmärkningar



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Om föräldern till detta [DataLabelFormat](../)-objekt är en [DataLabelCollection](../../datalabelcollection/)-samling av dataetiketter, så får den här egenskapen eller ställer in standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i [DataLabelCollection](../../datalabelcollection/)-samlingen. När den här egenskapen sätts till ett värde, sätts det värdet också för NumberFormat-egenskapen för alla dataetiketter i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" orsakar att alla DataLabels[i].NumberFormat blir lika med val). 

## Se även

* Klass [String](../../../system/string/)
* Klass [DataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)