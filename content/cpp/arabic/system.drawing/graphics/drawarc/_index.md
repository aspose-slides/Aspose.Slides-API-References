---
title: DrawArc()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يرسم القوس المحدد باستخدام القلم المحدد على السطح الممثَّل بواسطة الكائن الحالي.
type: docs
weight: 248
url: /ar/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) طريقة

يرسم القوس المحدد باستخدام القلم المحدد على السطح الممثَّل بواسطة الكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم القوس |
| x | **int32_t** | إحداثي X للزاوية اليسرى العليا للمستطيل الذي يحدد القطع الناقص |
| y | **int32_t** | إحداثي Y للزاوية اليسرى العليا للمستطيل الذي يحدد القطع الناقص |
| width | **int32_t** | عرض المستطيل الذي يحدد القطع الناقص |
| height | **int32_t** | ارتفاع المستطيل الذي يحدد القطع الناقص |
| startAngle | **int32_t** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من محور X إلى نقطة بدء القوس |
| sweepAngle | **int32_t** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من **startAngle** إلى نقطة نهاية القوس |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) طريقة

يرسم القوس المحدد باستخدام القلم المحدد على السطح الممثَّل بواسطة الكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم القوس |
| x | **float** | إحداثي X للزاوية اليسرى العليا للمستطيل الذي يحدد القطع الناقص |
| y | **float** | إحداثي Y للزاوية اليسرى العليا للمستطيل الذي يحدد القطع الناقص |
| width | **float** | عرض المستطيل الذي يحدد القطع الناقص |
| height | **float** | ارتفاع المستطيل الذي يحدد القطع الناقص |
| startAngle | **float** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من محور X إلى نقطة بدء القوس |
| sweepAngle | **float** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من **startAngle** إلى نقطة نهاية القوس |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) طريقة

يرسم القوس المحدد باستخدام القلم المحدد على السطح الممثَّل بواسطة الكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم القوس |
| rect | [Rectangle](../../rectangle/) | المستطيل الذي يحدد القطع الناقص |
| startAngle | **float** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من محور X إلى نقطة بدء القوس |
| sweepAngle | **float** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من **startAngle** إلى نقطة نهاية القوس |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) طريقة

يرسم القوس المحدد باستخدام القلم المحدد على السطح الممثَّل بواسطة الكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم القوس |
| rect | [RectangleF](../../rectanglef/) | المستطيل الذي يحدد القطع الناقص |
| startAngle | **float** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من محور X إلى نقطة بدء القوس |
| sweepAngle | **float** | الزاوية بالدرجات المقيسة في اتجاه عقرب الساعة من **startAngle** إلى نقطة نهاية القوس |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)