---
title: IGeometryPath
second_title: Aspose.Slides for Java مرجع API
description: يمثل مسار GeometryShape
type: docs
url: /ar/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

يمثل مسار GeometryShape
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPathData()](#getPathData--) | إرجاع مسار GeometryShape كمصفوفة من مقاطع المسار. |
| [removeAt(int index)](#removeAt-int-) | إزالة المقطع عند الفهرس المحدد لمسار الشكل الهندسي. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | إضافة خط إلى نهاية المسار |
| [lineTo(float x, float y)](#lineTo-float-float-) | إضافة خط إلى نهاية المسار |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | إضافة خط إلى الموقع المحدد في المسار |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | إضافة خط إلى الموقع المحدد في المسار |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | إضافة منحنى بيزير تكعيبي في نهاية المسار |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | إضافة منحنى بيزير تكعيبي في نهاية المسار |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | إضافة منحنى بيزير تكعيبي إلى الموقع المحدد في المسار |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | إضافة منحنى بيزير تكعيبي إلى الموقع المحدد في المسار |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | إضافة منحنى بيزير تربيعي في نهاية المسار |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | إضافة منحنى بيزير تربيعي في نهاية المسار |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | إضافة منحنى بيزير تربيعي إلى الموقع المحدد في المسار |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | إضافة منحنى بيزير تربيعي إلى الموقع المحدد في المسار |
| [closeFigure()](#closeFigure--) | إغلاق الشكل الحالي لهذا المسار |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | تعيين موضع النقطة التالية. |
| [moveTo(float x, float y)](#moveTo-float-float-) | تعيين موضع النقطة التالية. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | إلحاق القوس المحدد بالمسار. |
| [getFillMode()](#getFillMode--) | تعيين وضع التعبئة |
| [setFillMode(byte value)](#setFillMode-byte-) | تعيين وضع التعبئة |
| [getStroke()](#getStroke--) | تعيين مظهر الخط |
| [setStroke(boolean value)](#setStroke-boolean-) | تعيين مظهر الخط |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

الإرجاع:
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

إزالة المقطع عند الفهرس المحدد لمسار الشكل الهندسي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس للمسار الهندسي الذي يجب حذفه. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

إضافة خط إلى نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطة النهاية للخط |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

إضافة خط إلى نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X لنقطة النهاية للخط |
| y | float | إحداثي Y لنقطة النهاية للخط |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

إضافة خط إلى الموقع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطة النهاية |
| index | long | فهرس المقطع في PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

إضافة خط إلى الموقع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للنقطة |
| y | float | إحداثي Y للنقطة |
| index | long | فهرس المقطع في PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

إضافة منحنى بيزير تكعيبي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه الأولى |
| point2 | java.awt.geom.Point2D.Float | نقطة الاتجاه الثانية |
| point3 | java.awt.geom.Point2D.Float | نقطة النهاية |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

إضافة منحنى بيزير تكعيبي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه الأولى |
| y1 | float | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | إحداثي X لنقطة الاتجاه الثانية |
| y2 | float | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | إحداثي X لنقطة النهاية |
| y3 | float | إحداثي Y لنقطة النهاية |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

إضافة منحنى بيزير تكعيبي إلى الموقع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه الأولى |
| point2 | java.awt.geom.Point2D.Float | نقطة الاتجاه الثانية |
| point3 | java.awt.geom.Point2D.Float | نقطة النهاية |
| index | long | فهرس المقطع في PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

إضافة منحنى بيزير تكعيبي إلى الموقع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه الأولى |
| y1 | float | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | إحداثي X لنقطة الاتجاه الثانية |
| y2 | float | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | إحداثي X لنقطة النهاية |
| y3 | float | إحداثي Y لنقطة النهاية |
| index | long | فهرس المقطع في PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

إضافة منحنى بيزير تربيعي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه |
| point2 | java.awt.geom.Point2D.Float | نقطة النهاية |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

إضافة منحنى بيزير تربيعي في نهاية المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه |
| y1 | float | إحداثي Y لنقطة الاتجاه |
| x2 | float | إحداثي X لنقطة النهاية |
| y2 | float | إحداثي Y لنقطة النهاية |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

إضافة منحنى بيزير تربيعي إلى الموقع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطة الاتجاه |
| point2 | java.awt.geom.Point2D.Float | نقطة النهاية |
| index | long | فهرس المقطع في PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

إضافة منحنى بيزير تربيعي إلى الموقع المحدد في المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x1 | float | إحداثي X لنقطة الاتجاه |
| y1 | float | إحداثي Y لنقطة الاتجاه |
| x2 | float | إحداثي X لنقطة النهاية |
| y2 | float | إحداثي Y لنقطة النهاية |
| index | long | فهرس المقطع في PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

إغلاق الشكل الحالي لهذا المسار

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

تعيين موضع النقطة التالية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | موضع النقطة |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

تعيين موضع النقطة التالية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للنقطة |
| y | float | إحداثي Y للنقطة |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

إلحاق القوس المحدد بالمسار.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض المستطيل |
| heigth | float | ارتفاع المستطيل |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية القوس/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

تعيين وضع التعبئة

**الإرجاع:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

تعيين وضع التعبئة

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

تعيين مظهر الخط

**الإرجاع:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

تعيين مظهر الخط

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |