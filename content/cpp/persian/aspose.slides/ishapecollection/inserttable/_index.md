---
title: InsertTable()
second_title: مرجع API Aspose.Slides برای C++
description: یک جدول جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌کند.
type: docs
weight: 443
url: /fa/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) متد

یک جدول جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکسی که مشخص شده درج می‌نماید.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرمبنا که جدول در آن درج می‌شود. |
| x | **float** | مختصات x جدول، به واحد نقطه. |
| y | **float** | مختصات y جدول، به واحد نقطه. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | آرایه‌ای از مقادیر double که عرض ستون‌های جدول\\u2019s را نشان می‌دهد، به واحد نقطه. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | آرایه‌ای از مقادیر double که ارتفاع ردیف‌های جدول\\u2019s را نشان می‌دهد، به واحد نقطه. |

### مقدار بازگشتی

[ITable](../../itable/) جدید ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)