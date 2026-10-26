---
title: GetRange()
second_title: Aspose.Slides dla C++ – referencja API
description: Pobiera zakres danych wykresu.
type: docs
weight: 170
url: /pl/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() metoda


Pobiera zakres danych wykresu.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Wartość zwracana

Formuła zakresu danych komórek. Np.: \"Sheet1!$A$1:$C$4\"
## Uwagi




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)