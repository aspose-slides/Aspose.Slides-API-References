---
title: get_Format()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili properti pemformatan tingkat titik data. Baca IFormat.
type: docs
weight: 1
url: /id/aspose.slides.charts/chartdatapointlevel/get_format/
---
## ChartDataPointLevel::get_Format() metode

Mewakili properti pemformatan tingkat titik data. Baca [IFormat](../../iformat/).

```cpp
System::SharedPtr<IFormat> Aspose::Slides::Charts::ChartDataPointLevel::get_Format() override
```

## Catatan

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFormat](../../iformat/)
* Kelas [ChartDataPointLevel](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)