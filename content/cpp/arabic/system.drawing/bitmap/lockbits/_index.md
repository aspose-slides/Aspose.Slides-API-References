---
title: LockBits()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقفل صورة Bitmap في ذاكرة النظام.
type: docs
weight: 118
url: /ar/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) طريقة

يقفل [Bitmap](../) في ذاكرة النظام.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل يحدد المنطقة التي سيتم قفل الصورة فيها |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | يحدد مستوى الوصول إلى bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | تنسيق البيانات لهذا bitmap |

### قيمة الإرجاع

مؤشر مشترك إلى كائن BitmapData يحتوي على معلومات حول عملية القفل التي تم إجراؤها

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) طريقة

يقفل [Bitmap](../) في ذاكرة النظام.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل يحدد المنطقة التي سيتم قفل الصورة فيها |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | يحدد مستوى الوصول إلى bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | تنسيق البيانات لهذا bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | يحتوي على معلومات حول عملية القفل |

### قيمة الإرجاع

مؤشر مشترك إلى كائن BitmapData يحتوي على معلومات حول عملية القفل التي تم إجراؤها

## انظر أيضًا

* تعداد [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* تعداد [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* تعريف نوع [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* فئة [Rectangle](../../rectangle/)
* فئة [Bitmap](../)
* مساحة أسماء [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)