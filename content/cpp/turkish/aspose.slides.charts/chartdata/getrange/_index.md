---
title: GetRange()
second_title: Aspose.Slides for C++ API Referansı
description: Grafik veri aralığını alır.
type: docs
weight: 157
url: /tr/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() yöntemi


Grafik veri aralığını alır.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Dönüş Değeri

Hücrelerin veri aralığı formülü. Örn: \"Sheet1!$A$1:$C$4\"
## Açıklamalar




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ChartData](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)