---
title: ImageFlags
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل سمات بيانات البكسل التي يمثلها كائن Image.
type: docs
weight: 274
url: /ar/system.drawing.imaging/imageflags/
---
## ImageFlags تعداد

يمثل خصائص بيانات البكسل التي يمثلها كائن [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | قابل للتوسيع. |
| HasAlpha | 2 | يحتوي على معلومات ألفا. |
| HasTranslucent | 4 | هناك قيم ألفا أكبر من 0 وأقل من 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | يتم تمثيل بيانات البكسل في مساحة اللون RGB. |
| ColorSpaceCmyk | 32 | يتم تمثيل بيانات البكسل في مساحة اللون CMYK. |
| ColorSpaceGray | 64 | بيانات البكسل بتدرج رمادي. |
| ColorSpaceYcbcr | 128 | يتم تمثيل بيانات البكسل في مساحة اللون YCBCR. |
| ColorSpaceYcck | 256 | يتم تمثيل بيانات البكسل في مساحة اللون YCCK. |
| HasRealDpi | 4096 | معلومات DPI مخزنة في الصورة. |
| HasRealPixelSize | 8192 | حجم البكسل مخزن في الصورة. |
| ReadOnly | 65536 | بيانات البكسل للقراءة فقط. |
| Caching | 131072 | يمكن تخزينها مؤقتًا للوصول الأسرع. |

## انظر أيضًا

* النطاق [System::Drawing::Imaging](../)
* المكتبة [Aspose.Slides](../../)