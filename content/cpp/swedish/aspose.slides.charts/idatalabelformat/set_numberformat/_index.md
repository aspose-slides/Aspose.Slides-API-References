---
title: set_NumberFormat()
second_title: Aspose.Slides för C++ API-referens
description: "Representerar formatsträngen för DataLabels-objektet. Skriv System::String."
type: docs
weight: 40
url: /sv/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metod


Representerar formatsträngen för DataLabels-objektet. Skriv [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Anmärkningar

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Om föräldern till detta [DataLabelFormat](../../datalabelformat/)-objekt är en [DataLabelCollection](../../datalabelcollection/) samling av dataetiketter, hämtar eller anger denna egendom standardvärdet för NumberFormat-egenskapen för de nya dataetiketterna i [DataLabelCollection](../../datalabelcollection/)-samlingen. När denna egendom anges med ett värde, sätts också det värdet för NumberFormat-egenskapen för alla dataetiketter i [DataLabelCollection](../../datalabelcollection/)-samlingen (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" orsakar att alla DataLabels[i].NumberFormat blir lika med val).

## Se också

* Klass [String](../../../system/string/)
* Klass [IDataLabelFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)