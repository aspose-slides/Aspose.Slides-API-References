---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /fa/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

مسیر هندسی GeometryShape را نشان می‌دهد
## متدها

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | بخش را در اندیس مشخص‌شده از مسیر هندسی حذف می‌کند. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | خط را به انتهای مسیر اضافه می‌کند |
| [lineTo(float x, float y)](#lineTo-float-float-) | خط را به انتهای مسیر اضافه می‌کند |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | خط را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | خط را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | منحنی بیژیهٔ مکعبی را در انتهای مسیر اضافه می‌کند |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | منحنی بیژیهٔ مکعبی را در انتهای مسیر اضافه می‌کند |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | منحنی بیژیهٔ مکعبی را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | منحنی بیژیهٔ مکعبی را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | منحنی بیژیهٔ درجه‌دو را در انتهای مسیر اضافه می‌کند |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | منحنی بیژیهٔ درجه‌دو را در انتهای مسیر اضافه می‌کند |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | منحنی بیژیهٔ درجه‌دو را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | منحنی بیژیهٔ درجه‌دو را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند |
| [closeFigure()](#closeFigure--) | شکل فعلی این مسیر را می‌بندد |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [moveTo(float x, float y)](#moveTo-float-float-) | موقعیت نقطه بعدی را تنظیم می‌کند. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | قوس مشخص‌شده را به مسیر اضافه می‌کند. |
| [getFillMode()](#getFillMode--) | حالت پر کردن را تنظیم می‌کند |
| [setFillMode(byte value)](#setFillMode-byte-) | حالت پر کردن را تنظیم می‌کند |
| [getStroke()](#getStroke--) | ظاهر قلم‌ضربه را تنظیم می‌کند |
| [setStroke(boolean value)](#setStroke-boolean-) | ظاهر قلم‌ضربه را تنظیم می‌کند |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


مسیر هندسی GeometryShape را به‌صورت آرایه‌ای از بخش‌های مسیر برمی‌گرداند.

**برگشت:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


بخش را در اندیس مشخص‌شده از مسیر هندسی حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس مسیر هندسی که باید حذف شود. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


خط را به انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | نقطه پایانی خط |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


خط را به انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X نقطه پایانی خط |
| y | float | مختصات Y نقطه پایانی خط |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


خط را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | نقطه پایانی |
| index | long | اندیس بخش در PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


خط را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X نقطه |
| y | float | مختصات Y نقطه |
| index | long | اندیس بخش در PathData |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


منحنی بیژیهٔ مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌دار اول |
| point2 | android.graphics.PointF | نقطه جهت‌دار دوم |
| point3 | android.graphics.PointF | نقطه پایانی |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


منحنی بیژیهٔ مکعبی را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌دار اول |
| y1 | float | مختصات Y نقطه جهت‌دار اول |
| x2 | float | مختصات X نقطه جهت‌دار دوم |
| y2 | float | مختصات Y نقطه جهت‌دار دوم |
| x3 | float | مختصات X نقطه پایانی |
| y3 | float | مختصات Y نقطه پایانی |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


منحنی بیژیهٔ مکعبی را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌دار اول |
| point2 | android.graphics.PointF | نقطه جهت‌دار دوم |
| point3 | android.graphics.PointF | نقطه پایانی |
| index | long | اندیس بخش در PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


منحنی بیژیهٔ مکعبی را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌دار اول |
| y1 | float | مختصات Y نقطه جهت‌دار اول |
| x2 | float | مختصات X نقطه جهت‌دار دوم |
| y2 | float | مختصات Y نقطه جهت‌دار دوم |
| x3 | float | مختصات X نقطه پایانی |
| y3 | float | مختصات Y نقطه پایانی |
| index | long | اندیس بخش در PathData |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


منحنی بیژیهٔ درجه‌دو را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌دار |
| point2 | android.graphics.PointF | نقطه پایانی |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


منحنی بیژیهٔ درجه‌دو را در انتهای مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌دار |
| y1 | float | مختصات Y نقطه جهت‌دار |
| x2 | float | مختصات X نقطه پایانی |
| y2 | float | مختصات Y نقطه پایانی |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


منحنی بیژیهٔ درجه‌دو را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | نقطه جهت‌دار |
| point2 | android.graphics.PointF | نقطه پایانی |
| index | long | اندیس بخش در PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


منحنی بیژیهٔ درجه‌دو را به مکان مشخص‌شده‌ی مسیر اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | مختصات X نقطه جهت‌دار |
| y1 | float | مختصات Y نقطه جهت‌دار |
| x2 | float | مختصات X نقطه پایانی |
| y2 | float | مختصات Y نقطه پایانی |
| index | long | اندیس بخش در PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


شکل فعلی این مسیر را می‌بندد
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


موقعیت نقطه بعدی را تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | موقعیت نقطه |
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
| startAngle | float | زاویه شروع. |
| sweepAngle | float | زاویه sweep/ |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


حالت پر کردن را تنظیم می‌کند

**برگشت:**
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


ظاهر قلم‌ضربه را تنظیم می‌کند

**برگشت:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


ظاهر قلم‌ضربه را تنظیم می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |