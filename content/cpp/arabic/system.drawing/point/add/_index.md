---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف قيم العرض والارتفاع لكائن Size المحدد إلى قيم إحداثيات X و Y لكائن Point المحدد على التوالي.
type: docs
weight: 183
url: /ar/system.drawing/point/add/
---
## طريقة Point::Add(const Point\&, const Size\&) method

يقوم بإضافة قيم العرض والارتفاع للكائن [Size](../../size/) المحدد إلى قيم إحداثيات X و Y للكائن [Point](../) المحدد على التوالي.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | const [Point](../)\& | النقطة للترجمة |
| size | const [Size](../../size/)\& | الكائن [Size](../../size/) الذي يحدد القيم لإضافتها إلى قيم إحداثيات **point** |

### قيمة الإرجاع

كائن [Point](../) جديد تكون قيمة إحداثي X فيه مساوية لمجموع قيمة إحداثي X للـ **point** وقيمة العرض للـ **size**، وقيمة إحداثي Y تكون مساوية لمجموع قيمة إحداثي Y للـ **point** وقيمة الارتفاع للـ **size**.

## أنظر أيضًا

* الفئة [Point](../)
* الفئة [Size](../../size/)
* مساحة الاسم [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)