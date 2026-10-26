---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص شده قرار می‌دهد.
type: docs
weight: 560
url: /fa/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) متد

یک نسخهٔ کپی از shape مشخص شده ایجاد می‌کند و آن را در shape collection در ایندکس مشخص شده وارد می‌کند.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر-پایه‌ای که در آن shape کلون‌شده وارد می‌شود. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کلون. |
| x | **float** | مختصات x قاب shape کلون‌شده، بر حسب نقطه. |
| y | **float** | مختصات y قاب shape کلون‌شده، بر حسب نقطه. |
| width | **float** | عرض قاب shape کلون‌شده، بر حسب نقطه. |
| height | **float** | ارتفاع قاب shape کلون‌شده، بر حسب نقطه. |

### مقدار بازگشتی

[IShape](../../ishape/) تازه ساخته شده.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) متد

یک نسخهٔ کپی از shape مشخص شده ایجاد می‌کند و آن را در shape collection در ایندکس مشخص شده وارد می‌کند. shape جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر-پایه‌ای که در آن shape کلون‌شده وارد می‌شود. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کلون. |
| x | **float** | مختصات x قاب shape کلون‌شده، بر حسب نقطه. |
| y | **float** | مختصات y قاب shape کلون‌شده، بر حسب نقطه. |

### مقدار بازگشتی

[IShape](../../ishape/) تازه ساخته شده.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) متد

یک نسخهٔ کپی از shape مشخص شده ایجاد می‌کند و آن را در shape collection در ایندکس مشخص شده وارد می‌کند. shape کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر-پایه‌ای که در آن shape کلون‌شده وارد می‌شود. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کلون. |

### مقدار بازگشتی

[IShape](../../ishape/) تازه ساخته شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../ishape/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)