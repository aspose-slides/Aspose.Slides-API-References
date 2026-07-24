---
title: GetRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft den Diagrammdatenbereich ab.
type: docs
weight: 157
url: /de/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() method


Ruft den Diagrammdatenbereich ab.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Rückgabewert

Formel des Zellen-Datenbereichs. Z.B.: \"Sheet1!$A$1:$C$4\"
## Bemerkungen




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)