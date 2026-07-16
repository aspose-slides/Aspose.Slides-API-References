---
title: get_Worksheets()
second_title: Référence de l'API Aspose.Slides for C++
description: Récupère une collection de feuilles de calcul.
type: docs
weight: 1
url: /fr/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() méthode

Récupère une collection de feuilles de calcul.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Classe [ChartDataWorkbook](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)