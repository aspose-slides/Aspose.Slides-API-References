---
title: GetRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het gegevensbereik van de grafiek op.
type: docs
weight: 170
url: /nl/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() methode

Haalt het gegevensbereik van de grafiek op.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### Retourwaarde

Formule voor het celbereik. Bv: \"Sheet1!$A$1:$C$4\"
## Opmerkingen


```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)