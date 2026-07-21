---
title: GetCell()
second_title: Aspose.Slides для C++ справочник API
description: Получает ячейку, которую можно использовать для рядов или категорий диаграммы
type: docs
weight: 40
url: /ru/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа. |
| row | **int32_t** | Строка. |
| column | **int32_t** | Столбец. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) объект

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| row | **int32_t** | Строка. |
| column | **int32_t** | Столбец. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) объект

## IChartDataWorkbook::GetCell(int32_t, System::String) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| cellName | [System::String](../../../system/string/) | Имя ячейки. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) объект

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| cellName | [System::String](../../../system/string/) | Имя ячейки. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) объект

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) метод

Получает ячейку, которую можно использовать для рядов или категорий диаграммы

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа. |
| row | **int32_t** | Строка. |
| column | **int32_t** | Столбец. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение. |

### Возвращаемое значение

[Cell](../../../aspose.slides/cell/) объект

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [String](../../../system/string/)
* Класс [IChartDataWorkbook](../)
* Класс [Object](../../../system/object/)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)