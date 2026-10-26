---
title: GetTile()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ صورة بلاط لتعبئة النمط بألوان محددة.
type: docs
weight: 53
url: /ar/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) طريقة

Creates a tile image for the pattern fill with a specified colors.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | الخلفية [System::Drawing::Color](../../../system.drawing/color/) للنمط. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | المقدمة [System::Drawing::Color](../../../system.drawing/color/) للنمط. |

### قيمة الإرجاع

بلاط [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) طريقة

Creates a tile image for the pattern fill.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | القيمة الافتراضية [System::Drawing::Color](../../../system.drawing/color/)، المعرفة في كائن StyleEx الخاص بـ ShapeEx. قد تعتمد ألوان التعبئة على ذلك. |

### قيمة الإرجاع

بلاط [IImage](../../iimage/).

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [Color](../../../system.drawing/color/)
* فئة [IPatternFormat](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)