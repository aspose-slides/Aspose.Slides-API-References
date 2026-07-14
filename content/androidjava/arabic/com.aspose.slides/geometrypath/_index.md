---
title: GeometryPath
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مسار الهندسة لـ GeometryShape
type: docs
url: /ar/com.aspose.slides/geometrypath/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

يمثّل مسار الهندسة لـ GeometryShape
## المُنشئات

| المنشيء | الوصف |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | ينشئ مثلاً من GeometryPath |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPathData()](#getPathData--) | يرجع مسار الهندسة لـ GeometryShape كمصفوفة من قطاعات المسار. |
| [removeAt(int index)](#removeAt-int-) | يزيل القطاع في الفهرس المحدد من مسار الهندسة. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | يضيف خطًا إلى نهاية المسار |
| [lineTo(float x, float y)](#lineTo-float-float-) | يضيف خطًا إلى نهاية المسار |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | يضيف خطًا إلى الموضع المحدد في المسار |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | يضيف خطًا إلى الموضع المحدد في المسار |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | يضيف منحنى بيزير تكعيبي في نهاية المسار |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | يضيف منحنى بيزير تكعيبي في نهاية المسار |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | يضيف منحنى بيزير تكعيبي إلى الموضع المحدد في المسار |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | يضيف منحنى بيزير تكعيبي إلى الموضع المحدد في المسار |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | يضيف منحنى بيزير تربيعي في نهاية المسار |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | يضيف منحنى بيزير تربيعي في نهاية المسار |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | يضيف منحنى بيزير تربيعي إلى الموضع المحدد في المسار |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | يضيف منحنى بيزير تربيعي إلى الموضع المحدد في المسار |
| [closeFigure()](#closeFigure--) | يغلق الشكل الحالي لهذا المسار |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | يضبط موضع النقطة التالية. |
| [moveTo(float x, float y)](#moveTo-float-float-) | يضبط موضع النقطة التالية. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | يضيف القوس المحدد إلى المسار. |
| [getFillMode()](#getFillMode--) | يضبط وضع الملء |
| [setFillMode(byte value)](#setFillMode-byte-) | يضبط وضع الملء |
| [getStroke()](#getStroke--) | يضبط مظهر الخط |
| [setStroke(boolean value)](#setStroke-boolean-) | يضبط مظهر الخط |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

ينشئ مثلاً من GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

يرجع مسار الهندسة لـ GeometryShape كمصفوفة من قطاعات المسار.

**القيمة المرجعة:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل القطاع في الفهرس المحدد من مسار الهندسة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس مسار الهندسة الذي يجب حذفه. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

يضيف خطًا إلى نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | android.graphics.PointF | نقطة النهاية للخط |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

يضيف خطًا إلى نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لنقطة النهاية للخط |
| y | float | الإحداثي Y لنقطة النهاية للخط |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

يضيف خطًا إلى الموضع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | android.graphics.PointF | نقطة النهاية |
| index | long | فهرس القطاع في PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

يضيف خطًا إلى الموضع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للنقطة |
| y | float | الإحداثي Y للنقطة |
| index | long | فهرس القطاع في PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

يضيف منحنى بيزير تكعيبي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه الأولى |
| point2 | android.graphics.PointF | نقطة الاتجاه الثانية |
| point3 | android.graphics.PointF | نقطة النهاية |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

يضيف منحنى بيزير تكعيبي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه الأولى |
| y1 | float | الإحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | الإحداثي X لنقطة الاتجاه الثانية |
| y2 | float | الإحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | الإحداثي X لنقطة النهاية |
| y3 | float | الإحداثي Y لنقطة النهاية |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

يضيف منحنى بيزير تكعيبي إلى الموضع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه الأولى |
| point2 | android.graphics.PointF | نقطة الاتجاه الثانية |
| point3 | android.graphics.PointF | نقطة النهاية |
| index | long | فهرس القطاع في PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

يضيف منحنى بيزير تكعيبي إلى الموضع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه الأولى |
| y1 | float | الإحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | الإحداثي X لنقطة الاتجاه الثانية |
| y2 | float | الإحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | الإحداثي X لنقطة النهاية |
| y3 | float | الإحداثي Y لنقطة النهاية |
| index | long | فهرس القطاع في PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

يضيف منحنى بيزير تربيعي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه |
| point2 | android.graphics.PointF | نقطة النهاية |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

يضيف منحنى بيزير تربيعي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه |
| y1 | float | الإحداثي Y لنقطة الاتجاه |
| x2 | float | الإحداثي X لنقطة النهاية |
| y2 | float | الإحداثي Y لنقطة النهاية |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

يضيف منحنى بيزير تربيعي إلى الموضع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه |
| point2 | android.graphics.PointF | نقطة النهاية |
| index | long | فهرس القطاع في PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

يضيف منحنى بيزير تربيعي إلى الموضع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه |
| y1 | float | الإحداثي Y لنقطة الاتجاه |
| x2 | float | الإحداثي X لنقطة النهاية |
| y2 | float | الإحداثي Y لنقطة النهاية |
| index | long | فهرس القطاع في PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

يغلق الشكل الحالي لهذا المسار

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

يضبط موضع النقطة التالية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | android.graphics.PointF | موضع النقطة |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

يضبط موضع النقطة التالية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للنقطة |
| y | float | الإحداثي Y للنقطة |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

يضيف القوس المحدد إلى المسار.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض المستطيل |
| heigth | float | ارتفاع المستطيل |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية المسح/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

يضبط وضع الملء

**القيمة المرجعة:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

يضبط وضع الملء

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

يضبط مظهر الخط

**القيمة المرجعة:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

يضبط مظهر الخط

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |