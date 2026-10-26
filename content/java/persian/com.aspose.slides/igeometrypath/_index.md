---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: مسیر هندسی GeometryShape را نمایش می‌دهد
type: docs
url: /fa/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

نمایش مسیر هندسی GeometryShape
## متدها

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | بخش را در شاخص مشخص شده مسیر هندسی حذف می‌کند. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | خطی به انتهای مسیر اضافه می‌کند. |
| [lineTo(float x, float y)](#lineTo-float-float-) | خطی به انتهای مسیر اضافه می‌کند. |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | خطی به مکان مشخص‌شده مسیر اضافه می‌کند. |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | خطی به مکان مشخص‌شده مسیر اضافه می‌کند. |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | منحنی بزیه مکعبی را در انتهای مسیر اضافه می‌کند. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | منحنی بزیه مکعبی را در انتهای مسیر اضافه می‌کند. |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | منحنی بزیه مکعبی را به مکان مشخص‌شده مسیر اضافه می‌کند. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | منحنی بزیه مکعبی را به مکان مشخص‌شده مسیر اضافه می‌کند. |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | منحنی بزیه درجه دوم را در انتهای مسیر اضافه می‌کند. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | منحنی بزیه درجه دوم را در انتهای مسیر اضافه می‌کند. |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | منحنی بزیه درجه دوم را به مکان مشخص‌شده مسیر اضافه می‌کند. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | منحنی بزیه درجه دوم را به مکان مشخص‌شده مسیر اضافه می‌کند. |
| [closeFigure()](#closeFigure--) | شکل فعلی این مسیر را می‌بندد. |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [moveTo(float x, float y)](#moveTo-float-float-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | قوس مشخص‌شده را به مسیر اضافه می‌کند. |
| [getFillMode()](#getFillMode--) | حالت پر کردن را تنظیم می‌کند. |
| [setFillMode(byte value)](#setFillMode-byte-) | حالت پر کردن را تنظیم می‌کند. |
| [getStroke()](#getStroke--) | ظاهر خط را تنظیم می‌کند. |
| [setStroke(boolean value)](#setStroke-boolean-) | ظاهر خط را تنظیم می‌کند. |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر برمی‌گرداند.

**بازگشت:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


بخش را در شاخص مشخص شده مسیر هندسی حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | شاخص مسیر هندسی که باید حذف شود. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```


خطی به انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطه انتهایی خط |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


خطی به انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X نقطه انتهایی خط |
| y | float | مختصات Y نقطه انتهایی خط |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```


خطی به مکان مشخص‌شده مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


خطی به مکان مشخص‌شده مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X نقطه |
| y | float | مختصات Y نقطه |
| index | long | شاخص بخش در PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


منحنی بزیه مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری اول |
| point2 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری دوم |
| point3 | java.awt.geom.Point2D.Float | نقطه انتهایی |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


منحنی بزیه مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری اول |
| y1 | float | مختصات Y نقطه جهت‌گیری اول |
| x2 | float | مختصات X نقطه جهت‌گیری دوم |
| y2 | float | مختصات Y نقطه جهت‌گیری دوم |
| x3 | float | مختصات X نقطه انتهایی |
| y3 | float | مختصات Y نقطه انتهایی |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


منحنی بزیه مکعبی را به مکان مشخص‌شده مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری اول |
| point2 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری دوم |
| point3 | java.awt.geom.Point2D.Float | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


منحنی بزیه مکعبی را به مکان مشخص‌شده مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
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
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


منحنی بزیه درجه دوم را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری |
| point2 | java.awt.geom.Point2D.Float | نقطه انتهایی |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


منحنی بزیه درجه دوم را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری |
| y1 | float | مختصات Y نقطه جهت‌گیری |
| x2 | float | مختصات X نقطه انتهایی |
| y2 | float | مختصات Y نقطه انتهایی |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


منحنی بزیه درجه دوم را به مکان مشخص‌شده مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | نقطه جهت‌گیری |
| point2 | java.awt.geom.Point2D.Float | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


منحنی بزیه درجه دوم را به مکان مشخص‌شده مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری |
| y1 | float | مختصات Y نقطه جهت‌گیری |
| x2 | float | مختصات X نقطه انتهایی |
| y2 | float | مختصات Y نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


شکل فعلی این مسیر را می‌بندد

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```


موقعیت نقطه بعدی را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | موقعیت نقطه |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


موقعیت نقطه بعدی را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X نقطه |
| y | float | مختصات Y نقطه |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


قوس مشخص‌شده را به مسیر اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | عرض مستطیل |
| heigth | float | ارتفاع مستطیل |
| startAngle | float | زاویهٔ شروع |
| sweepAngle | float | زاویهٔ پیمایش |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


حالت پر کردن را تنظیم می‌کند

**بازگشت:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


حالت پر کردن را تنظیم می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


ظاهر خط را تنظیم می‌کند

**بازگشت:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


ظاهر خط را تنظیم می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |