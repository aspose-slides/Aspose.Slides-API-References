---
title: Add()
second_title: Aspose.Slides برای مرجع API C++
description: اگر دسته در مجموعه وجود داشته باشد، آن را برمی‌گرداند. در غیر این صورت، دستهٔ نمودار جدیدی از IChartDataCell ایجاد می‌کند و به مجموعه اضافه می‌نماید.
type: docs
weight: 92
url: /fa/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) متد


اگر دسته در مجموعه وجود داشته باشد، آن را برمی‌گرداند. در غیر این صورت، دستهٔ نمودار جدیدی از [IChartDataCell](../../ichartdatacell/) ایجاد می‌کند و به مجموعه اضافه می‌نماید.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) برای ایجاد دستهٔ نمودار استفاده می‌شود. |

### مقدار بازگشت

دستهٔ اضافه‌شده یا موجود.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) متد


یک [ChartCategory](../../chartcategory/) جدید از مقدار ایجاد می‌کند و به مجموعه اضافه می‌نماید.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | مقدار. |

### مقدار بازگشت

[IChartCategory](../../ichartcategory/) اضافه شد.

## توضیحات



این متد یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [ChartDataWorkbook](../../chartdataworkbook/) برای افزودن یا ویرایش مقادیر سلول استفاده می‌کنید، مطمئن شوید که از این کاربرگ استفاده نمی‌کنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شود نباید از 16711680 بیشتر باشد.



## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartCategory](../../ichartcategory/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [ChartCategoryCollection](../)
* کلاس [Object](../../../system/object/)
* فضای نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)