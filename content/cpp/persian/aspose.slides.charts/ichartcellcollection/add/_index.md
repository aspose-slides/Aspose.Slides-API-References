---
title: Add()
second_title: Aspose.Slides برای مرجع API C++
description: یک سلول جدید به مجموعه اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method

یک سلول جدید به مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | سلول جدید برای افزودن. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) method

از مقدار مشخص شده [IChartDataCell](../../ichartdatacell/) را ایجاد می‌کند و به مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | مقدار. |
## توضیحات

این روش یک worksheet با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن وارد می‌نماید. اگر از [IChartDataWorkbook](../../ichartdataworkbook/) برای افزودن یا ویرایش مقادیر [Cell](../../../aspose.slides/cell/) استفاده می‌کنید، مطمئن شوید که از این worksheet استفاده نمی‌کنید. حداکثر تعداد مقادیری که با استفاده از این روش افزوده می‌شود نباید از 16711680 عبور کند.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)