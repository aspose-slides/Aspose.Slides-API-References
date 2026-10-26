---
title: set_NumberFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de opmaakreeks voor het DataLabels-object voor. Schrijf System::String."
type: docs
weight: 40
url: /nl/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) methode

Stelt de opmaakreeks voor het DataLabels-object voor. Schrijf [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Opmerkingen


```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Als de bovenligger van dit [DataLabelFormat](../)-object een [DataLabelCollection](../../datalabelcollection/)-verzameling van data-labels is, dan haalt deze eigenschap de standaardwaarde van de NumberFormat-eigenschap op of stelt deze in voor de nieuwe data-labels in de [DataLabelCollection](../../datalabelcollection/)-verzameling. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap van alle data-labels in de [DataLabelCollection](../../datalabelcollection/)-verzameling (bijv. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" zorgt ervoor dat alle DataLabels[i].NumberFormat gelijk is aan val).


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [DataLabelFormat](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)