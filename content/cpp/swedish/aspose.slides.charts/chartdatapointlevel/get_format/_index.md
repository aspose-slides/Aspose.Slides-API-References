---
title: get_Format()
second_title: Aspose.Slides för C++ API-referens
description: Representerar formateringsegenskaper för datapunktsnivån. Läs IFormat.
type: docs
weight: 1
url: /sv/aspose.slides.charts/chartdatapointlevel/get_format/
---
## ChartDataPointLevel::get_Format() metod

Representerar formateringsegenskaper för datapunktsnivån. Läs [IFormat](../../iformat/).

```cpp
System::SharedPtr<IFormat> Aspose::Slides::Charts::ChartDataPointLevel::get_Format() override
```

## Anmärkningar

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFormat](../../iformat/)
* Klass [ChartDataPointLevel](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)