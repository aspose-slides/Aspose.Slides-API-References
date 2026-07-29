---
title: GetRange()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar diagramdataintervall.
type: docs
weight: 170
url: /sv/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() metod


Hämtar diagramdataintervall.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Returvärde

Formel för cellernas dataområde. T.ex: \"Sheet1!$A$1:$C$4\"
## Anmärkningar




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)