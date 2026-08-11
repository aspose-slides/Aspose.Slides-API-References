---
title: AddAutoShape()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را در انتهای مجموعه شکل‌ها اضافه می‌کند.
type: docs
weight: 352
url: /fa/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) متد

یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را در انتهای مجموعهٔ شکل‌ها اضافه می‌کند.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار برای افزودن. |
| x | **float** | مختصات x قاب شکل، بر حسب پوینت. |
| y | **float** | مختصات y قاب شکل، بر حسب پوینت. |
| width | **float** | عرض قاب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع قاب شکل، بر حسب پوینت. |

### مقدار بازگشتی

[IAutoShape](../../iautoshape/) جدید ایجاد شده.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) متد

یک شکل خودکار جدید ایجاد می‌کند و آن را در انتهای مجموعهٔ شکل‌ها اضافه می‌کند، به‌صورت اختیاری با قالب‌بندی پیش‌فرض الگو مقداردهی اولیه می‌کند.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار برای افزودن. |
| x | **float** | مختصات x قاب شکل، بر حسب پوینت. |
| y | **float** | مختصات y قاب شکل، بر حسب پوینت. |
| width | **float** | عرض قاب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع قاب شکل، بر حسب پوینت. |
| createFromTemplate | **bool** | True برای اعمال استایل پیش‌فرض الگو (استایل ساده، متن وسط‌چین، و نام غیرخالی) به شکل جدید؛ false برای ایجاد شکل با تمام خصوصیات تنظیم‌شده بر مقادیر پیش‌فرض. |

### مقدار بازگشتی

[IAutoShape](../../iautoshape/) جدید ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)