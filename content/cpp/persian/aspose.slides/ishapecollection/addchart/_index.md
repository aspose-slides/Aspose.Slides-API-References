---
title: AddChart()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌نماید و به انتهای مجموعهٔ اشکال اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) متد

یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌نماید و به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نموداری که باید اضافه شود. |
| x | **float** | مختصات x نمودار جدید، به واحد نقطه. |
| y | **float** | مختصات y نمودار جدید، به واحد نقطه. |
| width | **float** | عرض نمودار، به واحد نقطه. |
| height | **float** | ارتفاع نمودار، به واحد نقطه. |

### مقدار برگشتی

[Charts::IChart](../../../aspose.slides.charts/ichart/) تازه ایجاد شده.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) متد

یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری‌ها مقداردهی اولیه می‌نماید و به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نموداری که باید اضافه شود. |
| x | **float** | مختصات x نمودار جدید، به واحد نقطه. |
| y | **float** | مختصات y نمودار جدید، به واحد نقطه. |
| width | **float** | عرض نمودار، به واحد نقطه. |
| height | **float** | ارتفاع نمودار، به واحد نقطه. |
| initWithSample | **bool** | True برای مقداردهی اولیه نمودار جدید با داده‌ها و تنظیمات نمونه سری‌ها؛ false برای ایجاد نمودار بدون سری و فقط با حداقل تنظیمات، که باعث سرعت بیشتر در ایجاد می‌شود. |

### مقدار برگشتی

[Charts::IChart](../../../aspose.slides.charts/ichart/) تازه ایجاد شده.

## موارد مرتبط

* نوع شمارشی [ChartType](../../../aspose.slides.charts/charttype/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChart](../../../aspose.slides.charts/ichart/)
* کلاس [IShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)