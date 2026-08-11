---
title: FillPie()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يقوم بملء الفطيرة المحددة باستخدام الفرشاة المحددة على السطح الممثل بالكائن الحالي.
type: docs
weight: 274
url: /ar/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) طريقة

يقوم بملء الفطيرة المحددة باستخدام الفرشاة المحددة على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | فرشاة لاستخدامها عند ملء الفطيرة |
| x | int | إحداثي X للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص |
| y | int | إحداثي Y للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص |
| width | int | عرض المستطيل الذي يحدد القطع الناقص |
| height | int | ارتفاع المستطيل الذي يحدد القطع الناقص |
| startAngle | int | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | int | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة النهاية للفطيرة |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) طريقة

يقوم بملء الفطيرة المحددة باستخدام الفرشاة المحددة على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | فرشاة لاستخدامها عند ملء الفطيرة |
| x | **float** | إحداثي X للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص |
| y | **float** | إحداثي Y للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص |
| width | **float** | عرض المستطيل الذي يحدد القطع الناقص |
| height | **float** | ارتفاع المستطيل الذي يحدد القطع الناقص |
| startAngle | **float** | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | **float** | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة النهاية للفطيرة |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) طريقة

يقوم بملء الفطيرة المحددة باستخدام الفرشاة المحددة على السطح الممثل بالكائن الحالي.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | فرشاة لاستخدامها عند ملء الفطيرة |
| rect | [Rectangle](../../rectangle/) | المستطيل الذي يحدد القطع الناقص |
| startAngle | **float** | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من محور X إلى نقطة بدء الفطيرة |
| sweepAngle | **float** | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من **startAngle** إلى نقطة النهاية للفطيرة |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)