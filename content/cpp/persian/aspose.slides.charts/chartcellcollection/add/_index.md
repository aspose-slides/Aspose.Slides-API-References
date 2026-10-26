---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: سلول جدید را به مجموعه اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) متد

یک سلول جدید به مجموعه اضافه می‌کند.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | سلول جدید برای افزودن. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) متد

از مقدار مشخص شده [ChartDataCell](../../chartdatacell/) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | مقدار. |

## ملاحظات

این متد یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [ChartDataWorkbook](../../chartdataworkbook/) برای اضافه یا ویرایش مقادیر [Cell](../../../aspose.slides/cell/) استفاده می‌کنید، مطمئن شوید که از این کاربرگ استفاده نمی‌کنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید از 16711680 بیشتر باشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [ChartCellCollection](../)
* کلاس [Object](../../../system/object/)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)