---
title: GetCell()
second_title: مرجع API Aspose.Slides برای C++
description: سلولی را برمی‌گرداند که می‌توان برای سری‌ها یا دسته‌بندی‌های نمودار استفاده کرد
type: docs
weight: 40
url: /fa/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) متد

سلولی را برمی‌گرداند که می‌تواند برای سری‌ها یا دسته‌بندی‌های نمودار استفاده شود

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | نام کاربرگ. |
| row | **int32_t** | ردیف. |
| column | **int32_t** | ستون. |

### مقدار بازگشت

[Cell](../../../aspose.slides/cell/) شی

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) متد

سلولی را برمی‌گرداند که می‌تواند برای سری‌ها یا دسته‌بندی‌های نمودار استفاده شود

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | **int32_t** | شاخص کاربرگ. |
| row | **int32_t** | ردیف. |
| column | **int32_t** | ستون. |

### مقدار بازگشت

[Cell](../../../aspose.slides/cell/) شی

## IChartDataWorkbook::GetCell(int32_t, System::String) متد

سلولی را برمی‌گرداند که می‌تواند برای سری‌ها یا دسته‌بندی‌های نمودار استفاده شود

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | **int32_t** | شاخص کاربرگ. |
| cellName | [System::String](../../../system/string/) | نام سلول. |

### مقدار بازگشت

[Cell](../../../aspose.slides/cell/) شی

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) متد

سلولی را برمی‌گرداند که می‌تواند برای سری‌ها یا دسته‌بندی‌های نمودار استفاده شود

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | **int32_t** | شاخص کاربرگ. |
| cellName | [System::String](../../../system/string/) | نام سلول. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | مقدار. |

### مقدار بازگشت

[Cell](../../../aspose.slides/cell/) شی

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) متد

سلولی را برمی‌گرداند که می‌تواند برای سری‌ها یا دسته‌بندی‌های نمودار استفاده شود

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | **int32_t** | شاخص کاربرگ. |
| row | **int32_t** | ردیف. |
| column | **int32_t** | ستون. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | مقدار. |

### مقدار بازگشت

[Cell](../../../aspose.slides/cell/) شی

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [String](../../../system/string/)
* کلاس [IChartDataWorkbook](../)
* کلاس [Object](../../../system/object/)
* فضای نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)