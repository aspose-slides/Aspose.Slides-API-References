---
title: get_NumberFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de opmaakreeks voor het DataLabels-object voor. Lees System::String."
type: docs
weight: 27
url: /nl/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() methode


Stelt de opmaakreeks voor het DataLabels-object voor. Lees [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Opmerkingen



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Als de ouder van dit [DataLabelFormat](../)-object een [DataLabelCollection](../../datalabelcollection/)-collectie van datalabels is, dan krijgt deze eigenschap of stelt de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe datalabels in de [DataLabelCollection](../../datalabelcollection/)-collectie. Wanneer deze eigenschap wordt ingesteld op een waarde, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap voor alle datalabels in de [DataLabelCollection](../../datalabelcollection/)-collectie (d.w.z. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" zorgt ervoor dat alle DataLabels[i].NumberFormat gelijk is aan val). 


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [DataLabelFormat](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)