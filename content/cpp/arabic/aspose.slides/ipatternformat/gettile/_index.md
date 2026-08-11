---
title: GetTile()
second_title: Aspose.Slides للـ C++ مرجع API
description: ينشئ صورة بلاطة لتعبئة النمط بألوان محددة.
type: docs
weight: 53
url: /ar/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) طريقة

ينشئ صورة بلاطة لتعبئة النمط بألوان محددة.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | الخلفية [System::Drawing::Color](../../../system.drawing/color/) للنمط. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | المقدمة [System::Drawing::Color](../../../system.drawing/color/) للنمط. |

### قيمة الإرجاع

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) طريقة

ينشئ صورة بلاطة لتعبئة النمط.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | القيمة الافتراضية [System::Drawing::Color](../../../system.drawing/color/)، المعرفة في كائن StyleEx الخاص بـ ShapeEx. يمكن أن تعتمد ألوان التعبئة على ذلك. |

### قيمة الإرجاع

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [Color](../../../system.drawing/color/)
* فئة [IPatternFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)