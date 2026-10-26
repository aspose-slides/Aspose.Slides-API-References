---
title: InsertChart()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمودار جدید می‌سازد، آن را با داده‌ها و تنظیمات نمونه مقداردهی اولیه می‌کند و در مجموعهٔ اشکال در اندیس مشخص شده قرار می‌دهد.
type: docs
weight: 53
url: /fa/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) متد

یک نمودار جدید می‌سازد، آن را با داده‌ها و تنظیمات نمونه مقداردهی اولیه می‌کند و در مجموعهٔ شکل‌ها در اندیس مشخص شده قرار می‌دهد.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نموداری که باید ساخته شود. |
| x | **float** | مختصات x نمودار جدید، بر حسب نقطه. |
| y | **float** | مختصات y نمودار جدید، بر سماق نقطه. |
| width | **float** | عرض نمودار جدید، بر حسب نقطه. |
| height | **float** | ارتفاع نمودار جدید، بر حسب نقطه. |
| index | **int32_t** | اندیس صفر-پایه‌ای که نمودار جدید در مجموعهٔ شکل‌ها در آن قرار می‌گیرد. |

### مقدار بازگشتی

[Charts::IChart](../../../aspose.slides.charts/ichart/) جدید ایجاد شده.

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) متد

یک نمودار جدید می‌سازد، آن را با داده‌ها و تنظیمات نمونه مقداردهی اولیه می‌کند و در مجموعهٔ شکل‌ها در اندیس مشخص شده قرار می‌دهد.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نموداری که باید ساخته شود. |
| x | **float** | مختصات x نمودار جدید، بر حسب نقطه. |
| y | **float** | مختصات y نمودار جدید، بر حسب نقطه. |
| width | **float** | عرض نمودار جدید، بر حسب نقطه. |
| height | **float** | ارتفاع نمودار جدید، بر حسب نقطه. |
| index | **int32_t** | اندیس صفر-پایه‌ای که نمودار جدید در مجموعهٔ شکل‌ها در آن قرار می‌گیرد. |
| initWithSample | **bool** | ‎true برای مقداردهی اولیه نمودار جدید با داده‌ها و تنظیمات نمونه؛ ‎false برای ایجاد نمودار بدون سری و تنها با تنظیمات حداقل که باعث سرعت بیشتر می‌شود. |

### مقدار بازگشتی

[Charts::IChart](../../../aspose.slides.charts/ichart/) جدید ایجاد شده.

## مشاهده کنید

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChart](../../../aspose.slides.charts/ichart/)
* کلاس [IShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)