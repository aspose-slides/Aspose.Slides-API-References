---
title: DrawPie()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرسم الفطيرة المحددة باستخدام القلم المحدد على السطح الممثل بالكائن الحالي.
type: docs
weight: 261
url: /ar/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) طريقة


يرسم الفطيرة المحددة باستخدام القلم المحدد على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم الفطيرة |
| x | **int32_t** | إحداثي X للزاوية العليا اليسرى للمستطيل الذي يحدد الشكل البيضاوي |
| y | **int32_t** | إحداثي Y للزاوية العليا اليسرى للمستطيل الذي يحدد الشكل البيضاوي |
| width | **int32_t** | عرض المستطيل الذي يحدد الشكل البيضاوي |
| height | **int32_t** | ارتفاع المستطيل الذي يحدد الشكل البيضاوي |
| startAngle | **int32_t** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | **int32_t** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة انتهاء الفطيرة |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) طريقة


يرسم الفطيرة المحددة باستخدام القلم المحدد على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم الفطيرة |
| x | **float** | إحداثي X للزاوية العليا اليسرى للمستطيل الذي يحدد الشكل البيضاوي |
| y | **float** | إحداثي Y للزاوية العليا اليسرى للمستطيل الذي يحدد الشكل البيضاوي |
| width | **float** | عرض المستطيل الذي يحدد الشكل البيضاوي |
| height | **float** | ارتفاع المستطيل الذي يحدد الشكل البيضاوي |
| startAngle | **float** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | **float** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة انتهاء الفطيرة |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) طريقة


يرسم الفطيرة المحددة باستخدام القلم المحدد على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم الفطيرة |
| rect | [Rectangle](../../rectangle/) | المستطيل الذي يحدد الشكل البيضاوي |
| startAngle | **float** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | **float** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة انتهاء الفطيرة |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) طريقة


يرسم الفطيرة المحددة باستخدام القلم المحدد على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم الفطيرة |
| rect | [RectangleF](../../rectanglef/) | المستطيل الذي يحدد الشكل البيضاوي |
| startAngle | **float** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | **float** | زاوية بالدراجات تقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة انتهاء الفطيرة |

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Pen](../../pen/)
* فئة [Graphics](../)
* فئة [Rectangle](../../rectangle/)
* فئة [RectangleF](../../rectanglef/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)