---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API-referencia
description: Munkalapok egy gyűjteményét adja vissza.
type: docs
weight: 1
url: /hu/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() metódus


Visszaad egy munkalapok gyűjteményét.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## Megjegyzések


Példa:
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Osztály [IChartDataWorkbook](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)