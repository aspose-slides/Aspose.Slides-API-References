---
title: get_Label()
second_title: Aspose.Slides för C++ API-referens
description: Representerar datalabel för datapunktsnivå. Tillämpas för Treemap och Sunburst serietyper. Skrivskyddad IDataLabel.
type: docs
weight: 14
url: /sv/aspose.slides.charts/chartdatapointlevel/get_label/
---
## ChartDataPointLevel::get_Label() metod


Representerar dataetikett för datapunktsnivå. Tillämpas för Treemap och Sunburst-serietyper. Skrivskyddad [IDataLabel](../../idatalabel/).

```cpp
System::SharedPtr<IDataLabel> Aspose::Slides::Charts::ChartDataPointLevel::get_Label() override
```

## Anmärkningar



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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDataLabel](../../idatalabel/)
* Klass [ChartDataPointLevel](../)
* Namnutrymme [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)