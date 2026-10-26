---
title: GetCell()
second_title: Aspose.Slides for C++ API 參考
description: 取得可用於圖表系列或類別的儲存格
type: docs
weight: 40
url: /zh-hant/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) method

取得可用於圖表系列或類別的儲存格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 工作表的名稱。 |
| row | **int32_t** | 該列。 |
| column | **int32_t** | 該欄。 |

### 回傳值

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

取得可用於圖表系列或類別的儲存格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 該列。 |
| column | **int32_t** | 該欄。 |

### 回傳值

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) method

取得可用於圖表系列或類別的儲存格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 儲存格的名稱。 |

### 回傳值

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) method

取得可用於圖表系列或類別的儲存格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| cellName | [System::String](../../../system/string/) | 儲存格的名稱。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 該值。 |

### 回傳值

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) method

取得可用於圖表系列或類別的儲存格

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 工作表的索引。 |
| row | **int32_t** | 該列。 |
| column | **int32_t** | 該欄。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 該值。 |

### 回傳值

[Cell](../../../aspose.slides/cell/) object

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [String](../../../system/string/)
* Class [IChartDataWorkbook](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)