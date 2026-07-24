---
title: GetRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den Diagrammdatenbereich.
type: docs
weight: 170
url: /de/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() Methode


Ermittelt den Diagrammdatenbereich.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Rückgabewert

Formel des Zellbereichs. Beispiel: \"Sheet1!$A$1:$C$4\"
## Hinweise



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)