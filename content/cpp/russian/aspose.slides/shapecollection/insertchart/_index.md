---
title: InsertChart()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и настройками и вставляет её в коллекцию фигур в указанном индексе.
type: docs
weight: 92
url: /ru/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) метод

Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и настройками и вставляет её в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы для создания. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина новой диаграммы в пунктах. |
| height | **float** | Высота новой диаграммы в пунктах. |
| index | **int32_t** | Нулевой индекс, в котором вставлять новую диаграмму в коллекцию фигур. |

### Возвращаемое значение

Недавно созданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) метод

Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и настройками и вставляет её в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы для создания. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина новой диаграммы в пунктах. |
| height | **float** | Высота новой диаграммы в пунктах. |
| index | **int32_t** | Нулевой индекс, в котором вставлять новую диаграмму в коллекцию фигур. |
| initWithSample | **bool** | True, если необходимо инициализировать новую диаграмму образцовыми данными рядов и настройками; false, если следует создать диаграмму без рядов и только с минимальными настройками, что ускоряет создание. |

### Возвращаемое значение

Недавно созданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## См. также

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)