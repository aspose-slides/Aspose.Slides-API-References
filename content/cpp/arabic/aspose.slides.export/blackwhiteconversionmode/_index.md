---
title: BlackWhiteConversionMode
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: يوفر خيارات تتحكم في كيفية تحويل صور الشرائح إلى صور ذات لونين.
type: docs
weight: 820
url: /ar/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

يوفر خيارات تتحكم في كيفية تحويل صور الشرائح إلى صور ذات لونين.

```cpp
enum class BlackWhiteConversionMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Default | 0 | يحدد عدم وجود خوارزمية تحويل. سيتم استخدام الخوارزمية المنفذة في برنامج الترميز TIFF. (افتراضي) |
| Dithering | 1 | يحدد خوارزمية التهجيب (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | يحدد خوارزمية Floyd-Steinberg للتهجيب. |
| Auto | 3 | يحدد خوارزمية العتبة المحسوبة تلقائياً (Otsu). |
| AutoOtsu | 4 | يحدد خوارزمية عتبة Otsu المحسوبة تلقائياً. |
| Threshold25 | 5 | يحدد خوارزمية العتبة الثابتة (25%). |
| Threshold50 | 6 | يحدد خوارزمية العتبة الثابتة (50%). |
| Threshold75 | 7 | يحدد خوارزمية العتبة الثابتة (75%). |

## انظر أيضًا

* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)