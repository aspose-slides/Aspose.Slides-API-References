---
title: InsertChart()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و در مجموعهٔ شکل‌ها در شاخص مشخص‌شده درج می‌نماید.
type: docs
weight: 92
url: /fa/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method

یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و در مجموعهٔ شکل‌ها در شاخص مشخص‌شده درج می‌نماید.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نموداری که باید ایجاد شود. |
| x | **float** | مختصات x نمودار جدید، به نقاط. |
| y | **float** | مختصات y نمودار جدید، به نقاط. |
| width | **float** | عرض نمودار جدید، به نقاط. |
| height | **float** | ارتفاع نمودار جدید، به نقاط. |
| index | **int32_t** | شاخص صفر-پایه‌ای که نمودار جدید باید در آن در مجموعهٔ شکل‌ها درج شود. |

### مقدار بازگشتی

[Charts::IChart](../../../aspose.slides.charts/ichart/) جدیداً ایجاد شده.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method

یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌کند و در مجموعهٔ شکل‌ها در شاخص مشخص‌شده درج می‌نماید.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نموداری که باید ایجاد شود. |
| x | **float** | مختصات x نمودار جدید، به نقاط. |
| y | **float** | مختصات y نمودار جدید، به نقاط. |
| width | **float** | عرض نمودار جدید، به نقاط. |
| height | **float** | ارتفاع نمودار جدید، به نقاط. |
| index | **int32_t** | شاخص صفر-پایه‌ای که نمودار جدید باید در آن در مجموعهٔ شکل‌ها درج شود. |
| initWithSample | **bool** | درست برای مقداردهی اولیهٔ نمودار جدید با داده‌ها و تنظیمات نمونه سری‌ها؛ نادرست برای ایجاد نمودار بدون سری و تنها تنظیمات حداقلی، که سرعت ایجاد را افزایش می‌دهد. |

### مقدار بازگشتی

[Charts::IChart](../../../aspose.slides.charts/ichart/) جدیداً ایجاد شده.

## موارد مرتبط

* نوع شمارشی [ChartType](../../../aspose.slides.charts/charttype/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChart](../../../aspose.slides.charts/ichart/)
* کلاس [ShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)