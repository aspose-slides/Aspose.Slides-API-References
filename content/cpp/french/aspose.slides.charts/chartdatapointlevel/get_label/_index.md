---
title: get_Label()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente l'étiquette de données du niveau de point de données. Appliqué aux types Treemap et Sunburst sereis. Lecture seule IDataLabel.
type: docs
weight: 14
url: /fr/aspose.slides.charts/chartdatapointlevel/get_label/
---
## ChartDataPointLevel::get_Label() méthode

Représente l'étiquette de données du niveau de point de données. Appliqué aux types Treemap et Sunburst sereis. Lecture seule [IDataLabel](../../idatalabel/).

```cpp
System::SharedPtr<IDataLabel> Aspose::Slides::Charts::ChartDataPointLevel::get_Label() override
```

## Remarques



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

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDataLabel](../../idatalabel/)
* Classe [ChartDataPointLevel](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)