---
title: GeometryPath
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مسار الشكل الهندسي GeometryShape
type: docs
url: /ar/com.aspose.slides/geometrypath/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

يمثل مسار الشكل الهندسي GeometryShape
## المنشئات

| المنشيء | الوصف |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Creates instance of GeometryPath |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPathData()](#getPathData--) | Returns geometry path of GeometryShape as an array of path segments. |
| [removeAt(int index)](#removeAt-int-) | Removes segment at the specified index of the geometry path. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Adds line to the end of the path |
| [lineTo(float x, float y)](#lineTo-float-float-) | Adds line to the end of the path |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Adds line to the specified place of the path |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Adds line to the specified place of the path |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [closeFigure()](#closeFigure--) | Closes the current figure of this path |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Sets next point position. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sets next point position. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Appends the specified arc to the path. |
| [getFillMode()](#getFillMode--) | Sets fill mode |
| [setFillMode(byte value)](#setFillMode-byte-) | Sets fill mode |
| [getStroke()](#getStroke--) | Sets stroke appearance |
| [setStroke(boolean value)](#setStroke-boolean-) | Sets stroke appearance |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

إنشاء مثال من GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

إرجاع مسار الشكل الهندسي GeometryShape كمصفوفة من أجزاء المسار.

**الإرجاع:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

إزالة الجزء عند الفهرس المحدد من مسار الشكل الهندسي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | مؤشر مسار الشكل الهندسي الذي يجب حذفه. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

إضافة خط إلى نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطة النهاية للخط |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

إضافة خط إلى نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X لنقطة النهاية للخط |
| y | float | إحداثي Y لنقطة النهاية للخط |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

إضافة خط إلى المكان المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطة النهاية |
| index | long | فهرس الجزء في PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

إضافة خط إلى المكان المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للنقطة |
| y | float | إحداثي Y للنقطة |
| index | long | فهرس الجزء في PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

إضافة منحنى بيزير مكعب في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه الأولى |
| point2 | java.awt.geom.Point2D.Float | نقطة الاتجاه الثانية |
| point3 | java.awt.geom.Point2D.Float | نقطة النهاية |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

إضافة منحنى بيزير مكعب في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه الأولى |
| y1 | float | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | إحداثي X لنقطة الاتجاه الثانية |
| y2 | float | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | إحداثي X لنقطة النهاية |
| y3 | float | إحداثي Y لنقطة النهاية |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

إضافة منحنى بيزير مكعب إلى المكان المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه الأولى |
| point2 | java.awt.geom.Point2D.Float | نقطة الاتجاه الثانية |
| point3 | java.awt.geom.Point2D.Float | نقطة النهاية |
| index | long | فهرس الجزء في PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

إضافة منحنى بيزير مكعب إلى المكان المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه الأولى |
| y1 | float | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | إحداثي X لنقطة الاتجاه الثانية |
| y2 | float | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | إحداثي X لنقطة النهاية |
| y3 | float | إحداثي Y لنقطة النهاية |
| index | long | فهرس الجزء في PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

إضافة منحنى بيزير رباعي في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه |
| point2 | java.awt.geom.Point2D.Float | نقطة النهاية |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

إضافة منحنى بيزير رباعي في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه |
| y1 | float | إحداثي Y لنقطة الاتجاه |
| x2 | float | إحداثي X لنقطة النهاية |
| y2 | float | إحداثي Y لنقطة النهاية |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

إضافة منحنى بيزير رباعي إلى المكان المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه |
| point2 | java.awt.geom.Point2D.Float | نقطة النهاية |
| index | long | فهرس الجزء في PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

إضافة منحنى بيزير رباعي إلى المكان المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه |
| y1 | float | إحداثي Y لنقطة الاتجاه |
| x2 | float | إحداثي X لنقطة النهاية |
| y2 | float | إحداثي Y لنقطة النهاية |
| index | long | فهرس الجزء في PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

إغلاق الشكل الحالي لهذا المسار

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

تحديد موضع النقطة التالية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | موضع النقطة |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

تحديد موضع النقطة التالية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للنقطة |
| y | float | إحداثي Y للنقطة |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

إضافة القوس المحدد إلى المسار.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض المستطيل |
| heigth | float | ارتفاع المستطيل |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية القوس/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

ضبط وضع التعبئة

**الإرجاع:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

ضبط وضع التعبئة

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

ضبط مظهر الحد

**الإرجاع:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

ضبط مظهر الحد

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |