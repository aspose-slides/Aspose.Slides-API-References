---
title: GetTile()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ صورة بلاطة لتعبئة النمط بألوان محددة.
type: docs
weight: 53
url: /ar/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) طريقة

ينشئ صورة بلاطة لتعبئة النمط بألوان محددة.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | الخلفية [System::Drawing::Color](../../../system.drawing/color/) للنمط. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | المقدمة [System::Drawing::Color](../../../system.drawing/color/) للنمط. |

### قيمة الإرجاع

بلاطة [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) طريقة

ينشئ صورة بلاطة لتعبئة النمط.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | القيمة الافتراضية [System::Drawing::Color](../../../system.drawing/color/) |

### قيمة الإرجاع

بلاطة [IImage](../../iimage/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [Color](../../../system.drawing/color/)
* فئة [PatternFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)