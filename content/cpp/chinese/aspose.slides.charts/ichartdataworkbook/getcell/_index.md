---
title: GetCell()
second_title: Aspose.Slides C++ API 参考
description: 获取可用于图表系列或类别的单元格
type: docs
weight: 40
url: /zh/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) 方法

获取可用于图表系列或类别的单元格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名称。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |

### 返回值

[Cell](../../../aspose.slides/cell/) 对象

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) 方法

获取可用于图表系列或类别的单元格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |

### 返回值

[Cell](../../../aspose.slides/cell/) 对象

## IChartDataWorkbook::GetCell(int32_t, System::String) 方法

获取可用于图表系列或类别的单元格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 单元格的名称。 |

### 返回值

[Cell](../../../aspose.slides/cell/) 对象

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) 方法

获取可用于图表系列或类别的单元格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 单元格的名称。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

### 返回值

[Cell](../../../aspose.slides/cell/) 对象

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) 方法

获取可用于图表系列或类别的单元格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

### 返回值

[Cell](../../../aspose.slides/cell/) 对象

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [String](../../../system/string/)
* 类 [IChartDataWorkbook](../)
* 类 [Object](../../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)