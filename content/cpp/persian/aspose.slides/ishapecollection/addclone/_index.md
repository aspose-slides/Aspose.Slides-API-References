---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.
type: docs
weight: 495
url: /fa/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) متد

یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | شکل برای کلون کردن. |
| x | **float** | مختصات x چارچوب شکل کلون‌شده، به نقطه. |
| y | **float** | مختصات y چارچوب شکل کلون‌شده، به نقطه. |
| width | **float** | عرض چارچوب شکل کلون‌شده، به نقطه. |
| height | **float** | ارتفاع چارچوب شکل کلون‌شده، به نقطه. |

### مقدار بازگشت

[IShape](../../ishape/) جدید ایجاد شده.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) متد

یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کلون کردن. |
| x | **float** | مختصات x چارچوب شکل کلون‌شده، به نقطه. |
| y | **float** | مختصات y چارچوب شکل کلون‌شده، به نقطه. |

### مقدار بازگشت

[IShape](../../ishape/) جدید ایجاد شده.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) متد

یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کلون کردن. |

### مقدار بازگشت

[IShape](../../ishape/) جدید ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)