---
title: set_NumberFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de opmaakstring voor het DataLabels-object voor. Schrijf System::String."
type: docs
weight: 40
url: /nl/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) methode


Stelt de opmaakstring voor het DataLabels-object voor. Schrijf [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Opmerkingen



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Als de ouder van dit [DataLabelFormat](../../datalabelformat/)-object een [DataLabelCollection](../../datalabelcollection/)-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe gegevenslabels in de [DataLabelCollection](../../datalabelcollection/)-collectie. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap voor alle gegevenslabels in de [DataLabelCollection](../../datalabelcollection/)-collectie (d.w.z. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" veroorzaakt dat alle DataLabels[i].NumberFormat gelijk is aan val). 
## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IDataLabelFormat](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)