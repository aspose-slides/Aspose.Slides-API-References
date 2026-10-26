---
title: GeometryPath
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مسیر هندسی GeometryShape
type: docs
url: /fa/com.aspose.slides/geometrypath/
---
**ارث-برداری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

نمایانگر مسیر هندسی GeometryShape
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | یک نمونه از GeometryPath ایجاد می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getPathData()](#getPathData--) | مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر بازمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | بخش را در شاخص مشخص شده از مسیر هندسی حذف می‌کند. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | خطی به انتهای مسیر اضافه می‌کند |
| [lineTo(float x, float y)](#lineTo-float-float-) | خطی به انتهای مسیر اضافه می‌کند |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | خطی به مکان مشخصی از مسیر اضافه می‌کند |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | خطی به مکان مشخصی از مسیر اضافه می‌کند |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | منحنی Bezier مکعبی را به مکان مشخصی از مسیر اضافه می‌کند |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | منحنی Bezier مکعبی را به مکان مشخصی از مسیر اضافه می‌کند |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | منحنی Bezier درجه‌دو را در انتهای مسیر اضافه می‌کند |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | منحنی Bezier درجه‌دو را در انتهای مسیر اضافه می‌کند |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | منحنی Bezier درجه‌دو را به مکان مشخصی از مسیر اضافه می‌کند |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | منحنی Bezier درجه‌دو را به مکان مشخصی از مسیر اضافه می‌کند |
| [closeFigure()](#closeFigure--) | شکل فعلی این مسیر را می‌بندد |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [moveTo(float x, float y)](#moveTo-float-float-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | قوس مشخص شده را به مسیر افزود. |
| [getFillMode()](#getFillMode--) | حالت پر شدن را تنظیم می‌کند |
| [setFillMode(byte value)](#setFillMode-byte-) | حالت پر شدن را تنظیم می‌کند |
| [getStroke()](#getStroke--) | ظاهر خط را تنظیم می‌کند |
| [setStroke(boolean value)](#setStroke-boolean-) | ظاهر خط را تنظیم می‌کند |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

یک نمونه از GeometryPath ایجاد می‌کند

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر بازمی‌گرداند.

**باز می‌گردد:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

بخش را در شاخص مشخص شده از مسیر هندسی حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص بخشی از مسیر هندسی که باید حذف شود. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

خطی به انتهای مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point | android.graphics.PointF | نقطه انتهایی خط |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

خطی به انتهای مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X نقطه انتهایی خط |
| y | float | مختصات Y نقطه انتهایی خط |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

خطی به مکان مشخصی از مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point | android.graphics.PointF | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

خطی به مکان مشخصی از مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X نقطه |
| y | float | مختصات Y نقطه |
| index | long | شاخص بخش در PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌گیری اول |
| point2 | android.graphics.PointF | نقطه جهت‌گیری دوم |
| point3 | android.graphics.PointF | نقطه انتهایی |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری اول |
| y1 | float | مختصات Y نقطه جهت‌گیری اول |
| x2 | float | مختصات X نقطه جهت‌گیری دوم |
| y2 | float | مختصات Y نقطه جهت‌گیری دوم |
| x3 | float | مختصات X نقطه انتهایی |
| y3 | float | مختصات Y نقطه انتهایی |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

منحنی Bezier مکعبی را به مکان مشخصی از مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌گیری اول |
| point2 | android.graphics.PointF | نقطه جهت‌گیری دوم |
| point3 | android.graphics.PointF | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

منحنی Bezier مکعبی را به مکان مشخصی از مسیر اضافه می‌کند

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

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

منحنی Bezier درجه‌دو را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌گیری |
| point2 | android.graphics.PointF | نقطه انتهایی |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

منحنی Bezier درجه‌دو را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌گیری |
| y1 | float | مختصات Y نقطه جهت‌گیری |
| x2 | float | مختصات X نقطه انتهایی |
| y2 | float | مختصات Y نقطه انتهایی |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

منحنی Bezier درجه‌دو را به مکان مشخصی از مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌گیری |
| point2 | android.graphics.PointF | نقطه انتهایی |
| index | long | شاخص بخش در PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

منحنی Bezier درجه‌دو را به مکان مشخصی از مسیر اضافه می‌کند

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

شکل فعلی این مسیر را می‌بندد

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

موقعیت نقطه بعدی را تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| point | android.graphics.PointF | موقعیت نقطه |

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

قوس مشخص شده را به مسیر افزود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض مستطیل |
| heigth | float | ارتفاع مستطیل |
| startAngle | float | زاویه شروع. |
| sweepAngle | float | زاویه پیمایش |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

حالت پر شدن را تنظیم می‌کند

**باز می‌گردد:**
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

ظاهر خط را تنظیم می‌کند

**باز می‌گردد:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

ظاهر خط را تنظیم می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |