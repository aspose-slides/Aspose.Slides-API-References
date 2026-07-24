---
title: GetRange()
second_title: Aspose.Slides C++ API Referansı
description: Grafik veri aralığını alır.
type: docs
weight: 170
url: /tr/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() metod


Grafik veri aralığını alır.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Dönüş Değeri

Hücrelerin veri aralığı formülü. Örneğin: \"Sheet1!$A$1:$C$4\"
## Açıklamalar




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)