---
title: get_Format()
second_title: Référence de l'API Aspose.Slides for C++
description: Représente les propriétés de formatage du niveau de point de données. Lire IFormat.
type: docs
weight: 1
url: /fr/aspose.slides.charts/chartdatapointlevel/get_format/
---
## ChartDataPointLevel::get_Format() méthode

Représente les propriétés de formatage du niveau de point de données. Lire [IFormat](../../iformat/).

```cpp
System::SharedPtr<IFormat> Aspose::Slides::Charts::ChartDataPointLevel::get_Format() override
```

## Remarques

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFormat](../../iformat/)
* Classe [ChartDataPointLevel](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)