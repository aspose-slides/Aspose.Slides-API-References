---
title: InsertChart()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новую диаграмму, инициализирует её примерными данными серии и параметрами и вставляет её в коллекцию фигур в указанном индексе.
type: docs
weight: 53
url: /ru/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method


Создаёт новую диаграмму, инициализирует её примерными данными серии и параметрами и вставляет в коллекцию фигур в указанном индексе.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы для создания. |
| x | **float** | Координата x новой диаграммы, в пунктах. |
| y | **float** | Координата y новой диаграммы, в пунктах. |
| width | **float** | Ширина новой диаграммы, в пунктах. |
| height | **float** | Высота новой диаграммы, в пунктах. |
| index | **int32_t** | Нулевой-базовый индекс, в который нужно вставить новую диаграмму в коллекцию фигур. |

### Возвращаемое значение

Созданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method


Создаёт новую диаграмму, инициализирует её примерными данными серии и параметрами и вставляет в коллекцию фигур в указанном индексе.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы для создания. |
| x | **float** | Координата x новой диаграммы, в пунктах. |
| y | **float** | Координата y новой диаграммы, в пунктах. |
| width | **float** | Ширина новой диаграммы, в пунктах. |
| height | **float** | Высота новой диаграммы, в пунктах. |
| index | **int32_t** | Нулевой-базовый индекс, в который нужно вставить новую диаграмму в коллекцию фигур. |
| initWithSample | **bool** | true — инициализировать новую диаграмму примерными данными серии и параметрами; false — создать диаграмму без серий и только с минимальными настройками, что ускоряет создание. |

### Возвращаемое значение

Созданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## См. также

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChart](../../../aspose.slides.charts/ichart/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)