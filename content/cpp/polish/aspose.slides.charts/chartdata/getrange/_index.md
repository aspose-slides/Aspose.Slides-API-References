---
title: GetRange()
second_title: Aspose.Slides dla C++ – referencja API
description: Pobiera zakres danych wykresu.
type: docs
weight: 157
url: /pl/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() metoda


Pobiera zakres danych wykresu.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Wartość zwracana

Formuła zakresu danych komórek. Np: "Sheet1!$A$1:$C$4"
## Uwagi




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)