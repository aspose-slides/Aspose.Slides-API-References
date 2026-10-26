---
title: InsertAutoShape()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده درج می‌کند، قالب‌بندی پیش‌فرض الگو را اعمال می‌نماید.
type: docs
weight: 339
url: /fa/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) متد

یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده درج می‌کند، به‌همین‌صورت قالب‌بندی پیش‌فرض الگو اعمال می‌شود.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایه‌ای که شکل خودکار جدید در آن درج می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار برای درج. |
| x | **float** | مختصات x قاب شکل، بر حسب پوینت. |
| y | **float** | مختصات y قاب شکل، بر حسب پوینت. |
| width | **float** | عرض قاب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع قاب شکل، بر حسب پوینت. |

### مقدار بازگشت

[IAutoShape](../../iautoshape/) جدید ایجاد شده.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) متد

یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده درج می‌کند، به‌صورت اختیاری با استایل پیش‌فرض الگو مقداردهی اولیه می‌کند.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایه‌ای که شکل خودکار در آن درج می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار برای درج. |
| x | **float** | مختصات x قاب شکل، بر حسب پوینت. |
| y | **float** | مختصات y قاب شکل، بر حسب پوینت. |
| width | **float** | عرض قاب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع قاب شکل، بر حسب پوینت. |
| createFromTemplate | **bool** | True برای اعمال استایل پیش‌فرض الگو (از جمله نام غیر خالی، استایل ساده و متن وسط‌چین)؛ false برای ایجاد شکل با تمام ویژگی‌ها تنظیم شده بر پیش‌فرض‌ها. |

### مقدار بازگشت

[IAutoShape](../../iautoshape/) جدید ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [IShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)