---
title: GetRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt diagramgegevensbereik op.
type: docs
weight: 157
url: /nl/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() methode


Haalt diagramgegevensbereik op.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Retourwaarde

Formule voor het gegevensbereik van cellen. Bijv.: "Sheet1!$A$1:$C$4"
## Opmerkingen




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)