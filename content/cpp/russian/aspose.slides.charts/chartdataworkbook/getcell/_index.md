---
title: GetCell()
second_title: Справка API Aspose.Slides для C++
description: Получает ячейку, которую можно использовать для рядов или категорий диаграммы
type: docs
weight: 27
url: /ru/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа. |
| row | **int32_t** | Строка. |
| column | **int32_t** | Столбец. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) метод

Получает ячейку, którą можно использовать для рядов или категорий диаграммы

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| row | **int32_t** | Строка. |
| column | **int32_t** | Столбец. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| cellName | [System::String](../../../system/string/) | Имя ячейки. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| cellName | [System::String](../../../system/string/) | Имя ячейки. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| row | **int32_t** | Строка. |
| column | **int32_t** | Столбец. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [String](../../../system/string/)
* Класс [ChartDataWorkbook](../)
* Класс [Object](../../../system/object/)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)