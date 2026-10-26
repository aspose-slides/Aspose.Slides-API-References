---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /ar/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

يمثل مسار الشكل الهندسي لـ GeometryShape
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPathData()](#getPathData--) | يرجع مسار الشكل الهندسي لـ GeometryShape كمصفوفة من مقاطع المسار. |
| [removeAt(int index)](#removeAt-int-) | يزيل المقطع عند الفهرس المحدد لمسار الشكل الهندسي. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | يضيف خطًا إلى نهاية المسار |
| [lineTo(float x, float y)](#lineTo-float-float-) | يضيف خطًا إلى نهاية المسار |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | يضيف خطًا إلى الموقع المحدد في المسار |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | يضيف خطًا إلى الموقع المحدد في المسار |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | يضيف منحنى بيزيه مكعب في نهاية المسار |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | يضيف منحنى بيزيه مكعب في نهاية المسار |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | يضيف منحنى بيزيه مكعب إلى الموقع المحدد في المسار |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | يضيف منحنى بيزيه مكعب إلى الموقع المحدد في المسار |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | يضيف منحنى بيزيه تربيعي في نهاية المسار |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | يضيف منحنى بيزيه تربيعي في نهاية المسار |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | يضيف منحنى بيزيه تربيعي إلى الموقع المحدد في المسار |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | يضيف منحنى بيزيه تربيعي إلى الموقع المحدد في المسار |
| [closeFigure()](#closeFigure--) | يغلق الشكل الحالي لهذا المسار |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | يضبط موضع النقطة التالية. |
| [moveTo(float x, float y)](#moveTo-float-float-) | يضبط موضع النقطة التالية. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | يضيف القوس المحدد إلى المسار. |
| [getFillMode()](#getFillMode--) | يضبط وضع التعبئة |
| [setFillMode(byte value)](#setFillMode-byte-) | يضبط وضع التعبئة |
| [getStroke()](#getStroke--) | يضبط مظهر الحدود |
| [setStroke(boolean value)](#setStroke-boolean-) | يضبط مظهر الحدود |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

يرجع مسار الشكل الهندسي لـ GeometryShape كمصفوفة من مقاطع المسار.

**القيمة المرجعة:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل المقطع عند الفهرس المحدد لمسار الشكل الهندسي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس مسار الشكل الهندسي الذي يجب حذفه. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

يضيف خطًا إلى نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | android.graphics.PointF | نقطة النهاية للخط |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

يضيف خطًا إلى نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لنقطة النهاية للخط |
| y | float | الإحداثي Y لنقطة النهاية للخط |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

يضيف خطًا إلى الموقع المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | android.graphics.PointF | نقطة النهاية |
| index | long | فهرس المقطع في PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

يضيف خطًا إلى الموقع المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للنقطة |
| y | float | الإحداثي Y للنقطة |
| index | long | فهرس المقطع في PathData |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

يضيف منحنى بيزيه مكعب في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه الأولى |
| point2 | android.graphics.PointF | نقطة الاتجاه الثانية |
| point3 | android.graphics.PointF | نقطة النهاية |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

يضيف منحنى بيزيه مكعب في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه الأولى |
| y1 | float | الإحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | الإحداثي X لنقطة الاتجاه الثانية |
| y2 | float | الإحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | الإحداثي X لنقطة النهاية |
| y3 | float | الإحداثي Y لنقطة النهاية |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

يضيف منحنى بيزيه مكعب إلى الموقع المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه الأولى |
| point2 | android.graphics.PointF | نقطة الاتجاه الثانية |
| point3 | android.graphics.PointF | نقطة النهاية |
| index | long | فهرس المقطع في PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

يضيف منحنى بيزيه مكعب إلى الموقع المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه الأولى |
| y1 | float | الإحداثي Y لنقطة الاتجاه الأولى |
| x2 | float | الإحداثي X لنقطة الاتجاه الثانية |
| y2 | float | الإحداثي Y لنقطة الاتجاه الثانية |
| x3 | float | الإحداثي X لنقطة النهاية |
| y3 | float | الإحداثي Y لنقطة النهاية |
| index | long | فهرس المقطع في PathData |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

يضيف منحنى بيزيه تربيعي في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه |
| point2 | android.graphics.PointF | نقطة النهاية |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

يضيف منحنى بيزيه تربيعي في نهاية المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه |
| y1 | float | الإحداثي Y لنقطة الاتجاه |
| x2 | float | الإحداثي X لنقطة النهاية |
| y2 | float | الإحداثي Y لنقطة النهاية |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

يضيف منحنى بيزيه تربيعي إلى الموقع المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطة الاتجاه |
| point2 | android.graphics.PointF | نقطة النهاية |
| index | long | فهرس المقطع في PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

يضيف منحنى بيزيه تربيعي إلى الموقع المحدد في المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x1 | float | الإحداثي X لنقطة الاتجاه |
| y1 | float | الإحداثي Y لنقطة الاتجاه |
| x2 | float | الإحداثي X لنقطة النهاية |
| y2 | float | الإحداثي Y لنقطة النهاية |
| index | long | فهرس المقطع في PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

يغلق الشكل الحالي لهذا المسار
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

يضبط موضع النقطة التالية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | android.graphics.PointF | موضع النقطة |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

يضبط موضع النقطة التالية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للنقطة |
| y | float | الإحداثي Y للنقطة |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

يضيف القوس المحدد إلى المسار.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض المستطيل |
| heigth | float | ارتفاع المستطيل |
| startAngle | float | زاوية البدء. |
| sweepAngle | float | زاوية القوس |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

يضبط وضع التعبئة

**القيمة المرجعة:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

يضبط وضع التعبئة

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

يضبط مظهر الحدود

**القيمة المرجعة:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

يضبط مظهر الحدود

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |