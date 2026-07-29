---
title: GetCell()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar cellen som kan användas för diagramserier eller kategorier
type: docs
weight: 27
url: /sv/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metod

Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet. |
| row | **int32_t** | Raden. |
| column | **int32_t** | Kolumnen. |

### Returvärde

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metod

Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för kalkylbladet. |
| row | **int32_t** | Raden. |
| column | **int32_t** | Kolumnen. |

### Returvärde

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) metod

Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för kalkylbladet. |
| cellName | [System::String](../../../system/string/) | Namnet på cellen. |

### Returvärde

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metod

Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för kalkylbladet. |
| cellName | [System::String](../../../system/string/) | Namnet på cellen. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |

### Returvärde

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metod

Hämtar cellen som kan användas för diagramserier eller kategorier

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index för kalkylbladet. |
| row | **int32_t** | Raden. |
| column | **int32_t** | Kolumnen. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Värdet. |

### Returvärde

[Cell](../../../aspose.slides/cell/) object

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [String](../../../system/string/)
* Klass [ChartDataWorkbook](../)
* Klass [Object](../../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)