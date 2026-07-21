---
title: get_Worksheets()
second_title: Справочник API Aspose.Slides для C++
description: Получает коллекцию листов.
type: docs
weight: 1
url: /ru/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() method


Получает коллекцию листов.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Примечания


Пример: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Класс [ChartDataWorkbook](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)