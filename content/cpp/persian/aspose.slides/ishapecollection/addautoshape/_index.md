---
title: AddAutoShape()
second_title: مرجع API برای Aspose.Slides در C++
description: یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را در انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.
type: docs
weight: 313
url: /fa/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را در انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار که باید اضافه شود. |
| x | **float** | مختصات x چارچوب شکل، به نقطه. |
| y | **float** | مختصات y چارچوب شکل، به نقطه. |
| width | **float** | عرض چارچوب شکل، به نقطه. |
| height | **float** | ارتفاع چارچوب شکل، به نقطه. |

### Return Value

[IAutoShape](../../iautoshape/) تازه ساخته شده.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

یک شکل خودکار جدید ایجاد می‌کند و آن را در انتهای مجموعهٔ شکل‌ها اضافه می‌نماید؛ در صورت تمایل، با قالب‌بندی پیش‌فرض قالب می‌گیرد.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار که باید اضافه شود. |
| x | **float** | مختصات x چارچوب شکل، به نقطه. |
| y | **float** | مختصات y چارچوب شکل، به نقطه. |
| width | **float** | عرض چارچوب شکل، به نقطه. |
| height | **float** | ارتفاع چارچوب شکل، به نقطه. |
| createFromTemplate | **bool** | True برای اعمال استایل قالب پیش‌فرض (استایل ساده، متن مرکز شده و نام غیر خالی) به شکل جدید؛ false برای ایجاد شکل با تمام خصوصیات تنظیم شده به مقادیر پیش‌فرض. |

### Return Value

[IAutoShape](../../iautoshape/) تازه ساخته شده.

## See Also

* شمارش [ShapeType](../../shapetype/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [IShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)