---
title: GetCell()
second_title: Aspose.Slides for C++ API 參考
description: 取得可用於圖表系列或類別的儲存格
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) method

取得可用於圖表系列或類別的儲存格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名稱。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

取得可用於圖表系列或類別的儲存格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) method

取得可用於圖表系列或類別的儲存格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 儲存格的名稱。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) method

取得可用於圖表系列或類別的儲存格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 儲存格的名稱。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) method

取得可用於圖表系列或類別的儲存格

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 行。 |
| column | **int32_t** | 列。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

### 返回值

[Cell](../../../aspose.slides/cell/) object

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [String](../../../system/string/)
* 類別 [ChartDataWorkbook](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)