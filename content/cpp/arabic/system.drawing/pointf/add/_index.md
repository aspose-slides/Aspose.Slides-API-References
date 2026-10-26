---
title: Add()
second_title: مرجع API Aspose.Slides للـ C++
description: يضيف قيم العرض والارتفاع للكائن SizeF المحدد إلى قيم إحداثيات X و Y للكائن PointF المحدد على التوالي.
type: docs
weight: 144
url: /ar/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) طريقة

يقوم بإضافة قيم العرض والارتفاع للعنصر [SizeF](../../sizef/) المحدد إلى قيم إحداثيات X و Y للعنصر [PointF](../) المحدد على التوالي.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| point | const [PointF](../)\& | النقطة المراد نقلها |
| size | const [SizeF](../../sizef/)\& | الكائن [SizeF](../../sizef/) الذي يحدد القيم التي ستضيف إلى قيم إحداثيات **point** |

### قيمة الإرجاع

كائن [PointF](../) جديد تكون قيمة إحداثي X فيه مساوية لمجموع قيمة إحداثي X للـ **point** وقيمة العرض للـ **size**، وتكون قيمة إحداثي Y مساوية لمجموع قيمة إحداثي Y للـ **point** وقيمة الارتفاع للـ **size**.

## PointF::Add(const PointF\&, const Size\&) طريقة

يقوم بإضافة قيم العرض والارتفاع للعنصر [Size](../../size/) المحدد إلى قيم إحداثيات X و Y للعنصر [PointF](../) المحدد على التوالي.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| point | const [PointF](../)\& | النقطة المراد نقلها |
| size | const [Size](../../size/)\& | الكائن [Size](../../size/) الذي يحدد القيم التي ستضيف إلى قيم إحداثيات **point** |

### قيمة الإرجاع

كائن [PointF](../) جديد تكون قيمة إحداثي X فيه مساوية لمجموع قيمة إحداثي X للـ **point** وقيمة العرض للـ **size**، وتكون قيمة إحداثي Y مساوية لمجموع قيمة إحداثي Y للـ **point** وقيمة الارتفاع للـ **size**.

## أنظر أيضًا

* فئة [PointF](../)
* فئة [SizeF](../../sizef/)
* فئة [Size](../../size/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)