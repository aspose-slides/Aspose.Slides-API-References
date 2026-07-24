---
title: get_Label()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt das Datenetikett der Datenpunktstufe dar. Angewendet für Treemap- und Sunburst-Serientypen. Nur lesbar IDataLabel.
type: docs
weight: 14
url: /de/aspose.slides.charts/ichartdatapointlevel/get_label/
---
## IChartDataPointLevel::get_Label() Methode


Stellt das Datenetikett der Datenpunktstufe dar. Angewendet für Treemap- und Sunburst-Serien-Typen. Nur lesbar [IDataLabel](../../idatalabel/).

```cpp
virtual System::SharedPtr<IDataLabel> Aspose::Slides::Charts::IChartDataPointLevel::get_Label()=0
```

## Hinweise



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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDataLabel](../../idatalabel/)
* Klasse [IChartDataPointLevel](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)