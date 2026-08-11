---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: اگر دسته‌بندی در مجموعه وجود داشته باشد، آن را برمی‌گرداند. در غیر این صورت، دسته‌بندی جدید نمودار را از IChartDataCell ایجاد می‌کند و به مجموعه اضافه می‌نماید.
type: docs
weight: 53
url: /fa/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) متد


اگر دسته‌بندی در مجموعه وجود داشته باشد، آن را برمی‌گرداند. در غیر این صورت، دسته‌بندی جدید نمودار را از [IChartDataCell](../../ichartdatacell/) ایجاد می‌کند و به مجموعه اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) مورد استفاده برای ایجاد دسته‌بندی نمودار. |

### مقدار بازگشت

دسته‌بندی افزوده‌شده یا موجود.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) متد


[IChartCategory](../../ichartcategory/) جدیدی را از مقدار ایجاد کرده و به مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | مقدار. |

### مقدار بازگشت

[IChartCategory](../../ichartcategory/) اضافه شد.
## توضیحات



این متد یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [IChartDataWorkbook](../../ichartdataworkbook/) برای افزودن یا ویرایش مقادیر سلول استفاده کنید، مطمئن شوید که از این کاربرگ استفاده نکنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید از 16711680 بیشیابند.



## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartCategory](../../ichartcategory/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [IChartCategoryCollection](../)
* کلاس [Object](../../../system/object/)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)