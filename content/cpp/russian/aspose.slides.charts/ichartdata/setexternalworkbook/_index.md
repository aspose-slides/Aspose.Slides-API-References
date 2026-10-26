---
title: SetExternalWorkbook()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает внешнюю книгу как источник данных для диаграммы. Данные диаграммы будут обновлены из целевой книги.
type: docs
weight: 196
url: /ru/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) метод


Устанавливает внешнюю книгу как источник данных для диаграммы. [Chart](../../chart/) данные будут обновлены из целевой книги.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Путь к целевой книге |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) метод


Устанавливает внешнюю книгу как источник данных для диаграммы.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Путь к целевой книге |
| updateChartData | **bool** | Если значение false, будет обновлён только путь к книге. [Chart](../../chart/) данные не будут загружаться и обновляться из целевой книги. Можно использовать, когда целевая книга не существует или недоступна. Если значение true, данные диаграммы будут обновлены из целевой книги. |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)