---
title: SetSize()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضبط حجم الشريحة وفق النوع ويقيس المحتوى الموجود.
type: docs
weight: 53
url: /ar/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) طريقة

يضبط حجم الشريحة وفق النوع ويقيس المحتوى الموجود.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | حجم الشريحة المحدد مسبقًا لتطبيقه. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | وضعية تكبير المحتوى للاستخدام. |

## ملاحظات

تعيين أي قيمة غير [SlideSizeType::Custom](../../slidesizetype/) يضبط الـ [SlideSize::get_Size](../get_size/) بناءً على النوع المختار، مع الحفاظ على [SlideSize::get_Orientation](../get_orientation/).

## SlideSize::SetSize(float, float, SlideSizeScaleType) طريقة

يضبط أبعاد الشريحة صراحةً ويقيس المحتوى الموجود.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | **float** | عرض الشريحة الجديد بالنقاط. |
| height | **float** | ارتفاع الشريحة الجديد بالنقاط. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | وضعية تكبير المحتوى للاستخدام. |

## ملاحظات

هذا يعيد تعيين خاصية [SlideSize::get_Type](../get_type/) إلى [SlideSizeType::Custom](../../slidesizetype/) ويضبط الـ [Orientation](../../orientation/).

## انظر أيضًا

* تعداد [SlideSizeType](../../slidesizetype/)
* تعداد [SlideSizeScaleType](../../slidesizescaletype/)
* فئة [SlideSize](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)