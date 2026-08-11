---
title: SetSize()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: "يضبط حجم الشريحة حسب النوع ويعمل على تحجيم المحتوى الموجود. ضبط أي قيمة أخرى غير SlideSizeType::Custom يضبط ISlideSize::get_Size بناءً على النوع المحدد، مع الحفاظ على ISlideSize::get_Orientation."
type: docs
weight: 53
url: /ar/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) طريقة

يضبط حجم الشريحة حسب النوع ويعمل على تحجيم المحتوى الموجود. ضبط أي قيمة أخرى غير [SlideSizeType::Custom](../../slidesizetype/) يضبط [ISlideSize::get_Size](../get_size/) بناءً على النوع المحدد، مع الحفاظ على [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | حجم الشريحة المحدد مسبقًا للتطبيق. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | وضع تحجيم المحتوى المراد استخدامه. |
## ملاحظات

ضبط أي قيمة أخرى غير [SlideSizeType::Custom](../../slidesizetype/) يضبط [System::Drawing::Size](../../../system.drawing/size/) بناءً على النوع المحدد، مع الحفاظ على [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) طريقة

يضبط أبعاد الشريحة بشكل صريح ويعمل على تحجيم المحتوى الموجود. يعيد هذا تعيين قيمة [ISlideSize::get_Type](../get_type/) إلى [SlideSizeType::Custom](../../slidesizetype/) ويضبط [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| width | **float** | العرض الجديد للشريحة بالنقاط. |
| height | **float** | الارتفاع الجديد للشريحة بالنقاط. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | وضع تحجيم المحتوى المراد استخدامه. |
## ملاحظات

يعيد هذا تعيين الخاصية [ISlideSize::get_Type](../get_type/) إلى [SlideSizeType::Custom](../../slidesizetype/) ويضبط [Orientation](../../orientation/). 

## انظر أيضًا

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* فئة [ISlideSize](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)