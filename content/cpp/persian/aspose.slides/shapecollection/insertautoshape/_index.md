---
title: InsertAutoShape()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌نماید، با اعمال قالب‌بندی پیش‌فرض قالب.
type: docs
weight: 378
url: /fa/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) متد

یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌نماید، با اعمال قالب‌بندی پیش‌فرض قالب.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص صفرپایه‌ای که برای درج شکل خودکار جدید استفاده می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل خودکار برای درج. |
| x | **float** | مختصات x قاب shape، بر حسب نقاط. |
| y | **float** | مختصات y قاب shape، بر حسب نقاط. |
| width | **float** | عرض قاب shape، بر حسب نقاط. |
| height | **float** | ارتفاع قاب shape، بر حسب نقاط. |

### مقدار بازگشت

‏[IAutoShape](../../iautoshape/) تازه ایجاد شده.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) متد

یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌نماید؛ در صورت نیاز با استایل پیش‌فرض قالب مقداردهی اولیه می‌شود.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص صفرپایه‌ای که برای درج shape استفاده می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) shape برای درج. |
| x | **float** | مختصات x قاب shape، بر حسب نقاط. |
| y | **float** | مختصات y قاب shape، بر حسب نقاط. |
| width | **float** | عرض قاب shape، بر حسب نقاط. |
| height | **float** | ارتفاع قاب shape، بر حسب نقاط. |
| createFromTemplate | **bool** | True برای اعمال استایل پیش‌فرض قالب (شامل نام غیر خالی، سبک ساده، و متن مرکزی)؛ false برای ایجاد shape با تمامی خصوصیات تنظیم‌شده به پیش‌فرض‌ها. |

### مقدار بازگشت

‏[IAutoShape](../../iautoshape/) تازه ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)