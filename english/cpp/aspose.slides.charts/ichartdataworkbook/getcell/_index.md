---
title: GetCell()
second_title: Aspose.Slides for C++ API Reference
description: Gets the cell that can be used for chart series or categories
type: docs
weight: 40
url: /cpp/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) method


Gets the cell that can be used for chart series or categories

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Name of the worksheet. |
| row | **int32_t** | The row. |
| column | **int32_t** | The column. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) method


Gets the cell that can be used for chart series or categories

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| row | **int32_t** | The row. |
| column | **int32_t** | The column. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) method


Gets the cell that can be used for chart series or categories

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| cellName | [System::String](../../../system/string/) | Name of the cell. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) method


Gets the cell that can be used for chart series or categories

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index of the worksheet. |
| cellName | [System::String](../../../system/string/) | Name of the cell. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

### Return Value

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) method


Gets the cell that can be used for chart series or categories

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
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
* Class [IChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)