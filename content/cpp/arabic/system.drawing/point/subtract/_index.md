---
title: Subtract()
second_title: مرجع API Aspose.Slides للغة C++
description: يطرح قيم العرض والارتفاع لكائن Size المحدد من قيم إحداثيات X و Y لكائن Point المحدد على التوالي.
type: docs
weight: 196
url: /ar/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) طريقة

Subtracts the width and height values of the specified [Size](../../size/) object from the X and Y coordinates values of the specified [Point](../) object correspondingly.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | const [Point](../)\& | النقطة للترجمة |
| size | const [Size](../../size/)\& | الكائن [Size](../../size/) الذي يحدد القيم التي يتم طرحها من قيم إحداثيات **point** |

### قيمة الإرجاع

كائن [Point](../) جديد تكون قيمة إحداثي X مساوية لنتيجة طرح قيمة العرض **size** من قيمة إحداثي X **point** وتكون قيمة إحداثي Y مساوية لنتيجة طرح قيمة الارتفاع **size** من قيمة إحداثي Y **point**

## انظر أيضًا

* الفئة [Point](../)
* الفئة [Size](../../size/)
* النطاق [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)