---
title: GetRange()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar diagramdataintervall.
type: docs
weight: 157
url: /sv/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() metod

Hämtar diagramdataintervall.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```

### Returvärde

Cellernas dataområdeformel. T.ex.: "Sheet1!$A$1:$C$4"

## Anmärkningar


```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Se även

* Klass [String](../../../system/string/)
* Klass [ChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)