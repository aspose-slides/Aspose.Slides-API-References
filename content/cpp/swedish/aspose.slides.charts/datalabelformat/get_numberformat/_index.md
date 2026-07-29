---
title: get_NumberFormat()
second_title: Aspose.Slides för C++ API-referens
description: "Representerar formatsträngen för DataLabels-objektet. Läs System::String."
type: docs
weight: 27
url: /sv/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metod


Representerar formatsträngen för DataLabels-objektet. Läs [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Anmärkningar



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Om föräldern till detta [DataLabelFormat](../) objekt är en [DataLabelCollection](../../datalabelcollection/) samling av datamärkningar, så får denna egenskap eller sätter standardvärdet för NumberFormat-egenskapen för de nya datamärkningarna i [DataLabelCollection](../../datalabelcollection/)-samlingen. När denna egenskap sätts till ett värde, sätts också det värdet för NumberFormat-egenskapen för alla datamärkningar i [DataLabelCollection](../../datalabelcollection/)-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" gör att alla DataLabels[i].NumberFormat blir lika med val). 


## Se även

* Klass [String](../../../system/string/)
* Klass [DataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)