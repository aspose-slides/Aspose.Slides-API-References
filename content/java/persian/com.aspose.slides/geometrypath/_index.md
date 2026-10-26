---
title: GeometryPath
second_title: Aspose.Slides برای Java مرجع API
description: نمایش مسیر هندسی GeometryShape
type: docs
url: /fa/com.aspose.slides/geometrypath/
---
**ارث‌برداری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

نمایش مسیر هندسی GeometryShape
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | یک نمونه از GeometryPath را ایجاد می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getPathData()](#getPathData--) | مسیر هندسی GeometryShape را به عنوان آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | بخش را در شاخص مشخص‌شده از مسیر هندسی حذف می‌کند. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | یک خط را در انتهای مسیر اضافه می‌کند |
| [lineTo(float x, float y)](#lineTo-float-float-) | یک خط را در انتهای مسیر اضافه می‌کند |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | یک خط را در مکان مشخص شده مسیر اضافه می‌کند |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | یک خط را در مکان مشخص شده مسیر اضافه می‌کند |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | یک منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | یک منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | یک منحنی Bezier مکعبی را در مکان مشخص شده مسیر اضافه می‌کند |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | یک منحنی Bezier مکعبی را در مکان مشخص شده مسیر اضافه می‌کند |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | یک منحنی Bezier درجه دوم را در انتهای مسیر اضافه می‌کند |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | یک منحنی Bezier درجه دوم را در انتهای مسیر اضافه می‌کند |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | یک منحنی Bezier درجه دوم را در مکان مشخص شده مسیر اضافه می‌کند |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | یک منحنی Bezier درجه دوم را در مکان مشخص شده مسیر اضافه می‌کند |
| [closeFigure()](#closeFigure--) | شکل جاری این مسیر را می‌بندد |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [moveTo(float x, float y)](#moveTo-float-float-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | قوس مشخص‌شده را به مسیر اضافه می‌کند. |
| [getFillMode()](#getFillMode--) | حالت پر شدن را تنظیم می‌کند |
| [setFillMode(byte value)](#setFillMode-byte-) | حالت پر شدن را تنظیم می‌کند |
| [getStroke()](#getStroke--) | ظاهر قلم‌خط را تنظیم می‌کند |
| [setStroke(boolean value)](#setStroke-boolean-) | ظاهر قلم‌خط را تنظیم می‌کند |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

یک نمونه از GeometryPath را ایجاد می‌کند

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

مسیر هندسی GeometryShape را به عنوان آرایه‌ای از بخش‌های مسیر برمی‌گرداند.

**بازگشت:**  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

بخش را در شاخص مشخص‌شده از مسیر هندسی حذف می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص مسیر هندسی که باید حذف شود. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

یک خط را در انتهای مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطه انتهایی خط |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

یک خط را در انتهای مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X نقطه انتهایی خط |
| y | float | مختصات Y نقطه انتهایی خط |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

یک خط را در مکان مشخص شده مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

یک خط را در مکان مشخص شده مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X نقطه |
| y | float | مختصات Y نقطه |
| index | long | شاخص بخش در PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

یک منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری اول |
| point2 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری دوم |
| point3 | java.awt.geom.Point2D.Float | نقطه انتهایی |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

یک منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری اول |
| y1 | float | مختصات Y نقطه جهت‌گیری اول |
| x2 | float | مختصات X نقطه جهت‌گیری دوم |
| y2 | float | مختصات Y نقطه جهت‌گیری دوم |
| x3 | float | مختصات X نقطه انتهایی |
| y3 | float | مختصات Y نقطه انتهایی |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

یک منحنی Bezier مکعبی را در مکان مشخص شده مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری اول |
| point2 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری دوم |
| point3 | java.awt.geom.Point2D.Float | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

یک منحنی Bezier مکعبی را در مکان مشخص شده مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری اول |
| y1 | float | مختصات Y نقطه جهت‌گیری اول |
| x2 | float | مختصات X نقطه جهت‌گیری دوم |
| y2 | float | مختصات Y نقطه جهت‌گیری دوم |
| x3 | float | مختصات X نقطه انتهایی |
| y3 | float | مختصات Y نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

یک منحنی Bezier درجه دوم را در انتهای مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری |
| point2 | java.awt.geom.Point2D.Float | نقطه انتهایی |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

یک منحنی Bezier درجه دوم را در انتهای مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری |
| y1 | float | مختصات Y نقطه جهت‌گیری |
| x2 | float | مختصات X نقطه انتهایی |
| y2 | float | مختصات Y نقطه انتهایی |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

یک منحنی Bezier درجه دوم را در مکان مشخص شده مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری |
| point2 | java.awt.geom.Point2D.Float | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

یک منحنی Bezier درجه دوم را در مکان مشخص شده مسیر اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری |
| y1 | float | مختصات Y نقطه جهت‌گیری |
| x2 | float | مختصات X نقطه انتهایی |
| y2 | float | مختصات Y نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

شکل جاری این مسیر را می‌بندد

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

موقعیت نقطه بعدی را تنظیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | موقعیت نقطه |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

موقعیت نقطه بعدی را تنظیم می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X نقطه |
| y | float | مختصات Y نقطه |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

قوس مشخص‌شده را به مسیر اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض مستطیل |
| heigth | float | ارتفاع مستطیل |
| startAngle | float | زاویه شروع |
| sweepAngle | float | زاویه sweep |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

حالت پر شدن را تنظیم می‌کند

**بازگشت:**  
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

حالت پر شدن را تنظیم می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

ظاهر قلم‌خط را تنظیم می‌کند

**بازگشت:**  
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

ظاهر قلم‌خط را تنظیم می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |