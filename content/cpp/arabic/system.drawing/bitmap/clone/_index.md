---
title: Clone()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة من الكائن الحالي.
type: docs
weight: 183
url: /ar/system.drawing/bitmap/clone/
---
## Bitmap::Clone() طريقة

ينشئ نسخة من الكائن الحالي.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### قيمة الإرجاع

نسخة من الكائن الحالي.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) طريقة

ينشئ كائن [Bitmap](../) يمثل نسخة من منطقة من صورة البت ماب الممثلة بالكائن الحالي.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | المستطيل الذي يحدد المنطقة المراد نسخها |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | تنسيق البكسل للـ [Bitmap](../) الجديد |

### قيمة الإرجاع

الكائن [Bitmap](../) المُنشأ

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) طريقة

ينشئ كائن [Bitmap](../) يمثل نسخة من منطقة من صورة البت ماب الممثلة بالكائن الحالي.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | المستطيل الذي يحدد المنطقة المراد نسخها |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | تنسيق البكسل للـ [Bitmap](../) الجديد |

### قيمة الإرجاع

الكائن [Bitmap](../) المُنشأ

## انظر أيضًا

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)