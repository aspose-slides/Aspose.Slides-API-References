---
title: GetCell()
second_title: Aspose.Slides for C++ API Reference
description: Gets the cell that can be used for chart series or categories
type: docs
weight: 27
url: /cpp/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) method


Gets the cell that can be used for chart series or categories

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Name of the worksheet. |
| row | **int32_t** | The row. |
| column | **int32_t** | The column. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) method


Gets the cell that can be used for chart series or categories

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| row | **int32_t** | The row. |
| column | **int32_t** | The column. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) method


Gets the cell that can be used for chart series or categories

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| cellName | [System::String](../../../system/string/) | Name of the cell. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) method


Gets the cell that can be used for chart series or categories

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| cellName | [System::String](../../../system/string/) | Name of the cell. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) method


Gets the cell that can be used for chart series or categories

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| row | **int32_t** | The row. |
| column | **int32_t** | The column. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [String](../../../system/string/)
* Class [ChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)