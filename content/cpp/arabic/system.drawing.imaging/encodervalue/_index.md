---
title: EncoderValue
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحدد قيمة المعامل المرسلة إلى مُرمّز صورة JPEG أو TIFF.
type: docs
weight: 261
url: /ar/system.drawing.imaging/encodervalue/
---
## EncoderValue تعداد

Specifies the parameter value passed to a JPEG or TIFF image encoder.

```cpp
enum class EncoderValue
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ColorTypeCMYK | 0 | مساحة ألوان CMYK. |
| ColorTypeYCCK | 1 | مساحة ألوان YCCK. |
| CompressionLZW | 2 | طريقة ضغط LZW. |
| CompressionCCITT3 | 3 | يحدد طريقة ضغط CCITT3 لصورة TIFF. |
| CompressionCCITT4 | 4 | يحدد طريقة ضغط CCITT4 لصورة TIFF. |
| CompressionRle | 5 | يحدد طريقة ضغط RLE لصورة TIFF. |
| CompressionNone | 6 | يحدد عدم وجود ضغط لصورة TIFF. |
| ScanMethodInterlaced | 7 | الوضع المتشابك. |
| ScanMethodNonInterlaced | 8 | الوضع غير المتشابك. |
| VersionGif87 | 9 | يحدد الإصدار 87 لصورة TIFF. |
| VersionGif89 | 10 | يحدد الإصدار 89a لصورة GIF. |
| RenderProgressive | 11 | الوضع التقدمي. |
| RenderNonProgressive | 12 | الوضع غير التقدمي. |
| TransformRotate90 | 13 | يحدد دوران 90 درجة في اتجاه عقارب الساعة دون فقدان الجودة لصورة JPEG. |
| TransformRotate180 | 14 | يحدد دوران 180 درجة دون فقدان الجودة لصورة JPEG. |
| TransformRotate270 | 15 | يحدد دوران 270 درجة في اتجاه عقارب الساعة دون فقدان الجودة لصورة JPEG. |
| TransformFlipHorizontal | 16 | يحدد انعكاسًا أفقيًا دون فقدان الجودة لصورة JPEG. |
| TransformFlipVertical | 17 | يحدد انعكاسًا عموديًا دون فقدان الجودة لصورة JPEG. |
| MultiFrame | 18 | ترميز متعدد الإطارات. |
| LastFrame | 19 | الإطار الأخير لصورة متعددة الإطارات. |
| Flush | 20 | يجب إغلاق كائن المُرمِّز. |
| FrameDimensionTime | 21 | يحدد بُعد إطار الوقت لصورة GIF. |
| FrameDimensionResolution | 22 | بُعد إطار الدقة. |
| FrameDimensionPage | 23 | يحدد بُعد إطار الصفحة لصورة TIFF. |

## انظر أيضًا

* النطاق [System::Drawing::Imaging](../)
* المكتبة [Aspose.Slides](../../)