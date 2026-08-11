---
title: GetCell()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يجلب الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات
type: docs
weight: 27
url: /ar/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) طريقة

يجلب الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | اسم ورقة العمل. |
| row | **int32_t** | الصف. |
| column | **int32_t** | العمود. |

### قيمة الإرجاع

[Cell](../../../aspose.slides/cell/) كائن

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) طريقة

يجلب الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل. |
| row | **int32_t** | الصف. |
| column | **int32_t** | العمود. |

### قيمة الإرجاع

[Cell](../../../aspose.slides/cell/) كائن

## ChartDataWorkbook::GetCell(int32_t, System::String) طريقة

يجلب الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل. |
| cellName | [System::String](../../../system/string/) | اسم الخلية. |

### قيمة الإرجاع

[Cell](../../../aspose.slides/cell/) كائن

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) طريقة

يجلب الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل. |
| cellName | [System::String](../../../system/string/) | اسم الخلية. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | القيمة. |

### قيمة الإرجاع

[Cell](../../../aspose.slides/cell/) كائن

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) طريقة

يجلب الخلية التي يمكن استخدامها لسلاسل المخطط أو الفئات

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | **int32_t** | فهرس ورقة العمل. |
| row | **int32_t** | الصف. |
| column | **int32_t** | العمود. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | القيمة. |

### قيمة الإرجاع

[Cell](../../../aspose.slides/cell/) كائن

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataCell](../../ichartdatacell/)
* فئة [String](../../../system/string/)
* فئة [ChartDataWorkbook](../)
* فئة [Object](../../../system/object/)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)