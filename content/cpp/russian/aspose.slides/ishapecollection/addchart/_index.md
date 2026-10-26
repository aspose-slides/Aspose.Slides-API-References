---
title: AddChart()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новую диаграмму, инициализирует её образцовыми данными серий и настройками и добавляет её в конец коллекции фигур.
type: docs
weight: 27
url: /ru/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) метод

Создаёт новую диаграмму, инициализирует её образцовыми данными серий и настройками и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы для добавления. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина диаграммы в пунктах. |
| height | **float** | Высота диаграммы в пунктах. |

### Возвращаемое значение

Новосозданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) метод

Создаёт новую диаграмму, инициализирует её образцовыми данными серий и настройками и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы для добавления. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина диаграммы в пунктах. |
| height | **float** | Высота диаграммы в пунктах. |
| initWithSample | **bool** | True, чтобы инициализировать новую диаграмму образцовыми данными серий и настройками; false, чтобы создать диаграмму без серий и только с минимальными настройками, что ускоряет создание. |

### Возвращаемое значение

Новосозданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## См. также

* Перечисление [ChartType](../../../aspose.slides.charts/charttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IChart](../../../aspose.slides.charts/ichart/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)