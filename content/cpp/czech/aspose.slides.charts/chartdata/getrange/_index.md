---
title: GetRange()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá rozsah dat grafu.
type: docs
weight: 157
url: /cs/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() metoda


Získá rozsah dat grafu.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Návratová hodnota

Vzorec rozsahu dat buněk. Např.: \"Sheet1!$A$1:$C$4\"

## Poznámky




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [ChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)