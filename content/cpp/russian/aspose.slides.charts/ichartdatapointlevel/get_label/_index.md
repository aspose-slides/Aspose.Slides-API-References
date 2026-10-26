---
title: get_Label()
second_title: Ссылка на API Aspose.Slides для C++
description: Представляет метку данных уровня точки данных. Применяется для типов Treemap и Sunburst series. Только для чтения IDataLabel.
type: docs
weight: 14
url: /ru/aspose.slides.charts/ichartdatapointlevel/get_label/
---
## IChartDataPointLevel::get_Label() метод


Представляет метку данных уровня точки данных. Применяется для типов Treemap и Sunburst series. Только для чтения [IDataLabel](../../idatalabel/).

```cpp
virtual System::SharedPtr<IDataLabel> Aspose::Slides::Charts::IChartDataPointLevel::get_Label()=0
```

## Примечания



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Sunburst, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(0)->get_DataPointLevels()->idx_get(1);

dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowCategoryName(false);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowValue(true);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowSeriesName(true);

dataPointLevel = series->get_DataPoints()->idx_get(12)->get_DataPointLevels()->idx_get(1);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDataLabel](../../idatalabel/)
* Класс [IChartDataPointLevel](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)