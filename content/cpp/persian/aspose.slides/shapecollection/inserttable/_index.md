---
title: InsertTable()
second_title: Aspose.Slides برای مستندات API C++
description: یک جدول جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در شاخص مشخص شده درج می‌کند.
type: docs
weight: 482
url: /fa/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) متد

یک جدول جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در شاخص مشخص شده درج می‌کند.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر-پایه‌ای که جدول در آن درج می‌شود. |
| x | **float** | مختصات x جدول، به واحد نقطه. |
| y | **float** | مختصات y جدول، به واحد نقطه. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | یک آرایهٔ از نوع double که عرض ستون‌های جدول را نشان می‌دهد، به واحد نقطه. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | یک آرایهٔ از نوع double که ارتفاع ردیف‌های جدول را نشان می‌دهد، به واحد نقطه. |

### مقدار بازگشتی

تازه ایجاد شده [ITable](../../itable/).

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ITable](../../itable/)
* کلاس [ShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)