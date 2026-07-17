---
title: GetCell()
second_title: Aspose.Slides C++ API 参考
description: 获取可用于图表系列或类别的单元格
type: docs
weight: 27
url: /zh/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) 方法


获取可用于图表系列或类别的单元格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名称。 |
| row | **int32_t** | 行号。 |
| column | **int32_t** | 列号。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) 方法


获取可用于图表系列或类别的单元格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 行号。 |
| column | **int32_t** | 列号。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) 方法


获取可用于图表系列或类别的单元格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 单元格的名称。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) 方法


获取可用于图表系列或类别的单元格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 单元格的名称。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) 方法


获取可用于图表系列或类别的单元格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 行号。 |
| column | **int32_t** | 列号。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [String](../../../system/string/)
* Class [ChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)