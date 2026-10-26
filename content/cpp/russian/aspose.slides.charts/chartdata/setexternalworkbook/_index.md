---
title: SetExternalWorkbook()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы. Данные диаграммы будут обновлены из целевой рабочей книги.
type: docs
weight: 183
url: /ru/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) метод

Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы. Данные [Chart](../../chart/) будут обновлены из целевой рабочей книги.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Путь к целевой рабочей книге |

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) метод

Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Путь к целевой рабочей книге |
| updateChartData | **bool** | Если значение ложное, будет обновлен только путь к рабочей книге. Данные [Chart](../../chart/) не будут загружены и обновлены из целевой рабочей книги. Можно использовать, когда целевая рабочая книга не существует или недоступна. Если значение истинно, данные диаграммы будут обновлены из целевой рабочей книги. |

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ChartData](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)