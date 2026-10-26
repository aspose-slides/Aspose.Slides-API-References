---
title: get_Worksheets()
second_title: Aspose.Slides для C++ справочник API
description: Получает коллекцию листов.
type: docs
weight: 1
url: /ru/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() метод


Получает коллекцию листов.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
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




## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Класс [IChartDataWorkbook](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)