---
title: AddGroupShape()
second_title: راهنمای API Aspose.Slides برای C++
description: یک شکل گروهی خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. چارچوب group\u2019s به‌صورت خودکار تنظیم می‌شود تا هر شکلی که به آن اضافه شود، جا بگیرد.
type: docs
weight: 352
url: /fa/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() متد

یک شکل گروهی خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. چارچوب گروه\\u2019s به‌طور خودکار تنظیم می‌شود تا هر شکلی که به آن اضافه شود، جا بگیرد.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### مقدار بازگشت

[IGroupShape](../../igroupshape/) تازه ایجاد شده.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) متد

یک شکل گروهی جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌نماید و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) حاوی محتوای برداری برای تبدیل به اشکال. |
| x | **float** | مختصات x چارچوب گروه\\u2019s، بر حسب نقاط. |
| y | **float** | مختصات y چارچوب گروه\\u2019s، بر حسب نقاط. |
| width | **float** | عرض چارچوب گروه\\u2019s، بر حسب نقاط. |
| height | **float** | ارتفاع چارچوب گروه\\u2019s، بر حسب نقاط. |

### مقدار بازگشت

[IGroupShape](../../igroupshape/) تازه ایجاد شده.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [IShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)