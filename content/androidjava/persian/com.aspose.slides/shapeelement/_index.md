---
title: ShapeElement
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک قسمت از شکل را که دارای خطوط مرزی و ویژگی‌های پر کردن یکسان است نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/shapeelement/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

یک قسمت از شکل را که دارای خطوط مرزی و ویژگی‌های پر کردن یکسان است نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getParentShape()](#getParentShape--) | یک Shape_PPT را که عنصر برای آن ساخته شده است باز می‌گرداند. |
| [getPathPoints()](#getPathPoints--) | یک آرایه از نقاط که هندسه مسیر عنصر را تعریف می‌کند دریافت می‌کند. |
| [getPathTypes()](#getPathTypes--) | یک آرایه از مقادیر بایتی که نوع هر نقطه در مسیر عنصر را مشخص می‌کند دریافت می‌کند. |
| [getFillSource()](#getFillSource--) | اطلاعاتی درباره نحوه پر کردن یک عنصر را باز می‌گرداند. |
| [getStrokeSource()](#getStrokeSource--) | اطلاعاتی درباره نحوه کشیدن خط دور (stroke) یک عنصر را باز می‌گرداند. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

یک Shape_PPT را که عنصر برای آن ساخته شده است باز می‌گرداند. فقط-خواندنی [Shape](../../com.aspose.slides/shape).

**بازگشت:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

یک آرایه از نقاط که هندسه مسیر عنصر را تعریف می‌کند دریافت می‌کند.

**بازگشت:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

یک آرایه از مقادیر بایتی که نوع هر نقطه در مسیر عنصر را مشخص می‌کند دریافت می‌کند.

**0** نشان می‌دهد که نقطه شروع یک شکل (figure) است.

**1** نشان می‌دهد که نقطه یکی از دو نقطه انتهای یک خط است.

**3** نشان می‌دهد که نقطه یک نقطه انتهایی یا نقطه کنترل یک منحنی بزیه (Bezier) مکعبی است.

**7** تمام بیت‌ها به جز سه بیت کم‌اهمیت را ماسک می‌کند، که نوع نقطه را مشخص می‌کنند.

**16** مشخص می‌کند که بخش متناظر خط‌چین است.

**32** مشخص می‌کند که نقطه یک نشانگر است.

**128** مشخص می‌کند که نقطه آخرین نقطه در یک زیرمسیر بسته (figure) است.

**129** نشان می‌دهد که نقطه داده‌ای است که هم نقطه انتهای یک قطعه خط و هم آخرین نقطه یک زیرمسیر بسته است.

**بازگشت:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

اطلاعاتی درباره نحوه پر کردن یک عنصر را باز می‌گرداند. فقط-خواندنی [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**بازگشت:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

اطلاعاتی درباره نحوه کشیدن خط دور (stroke) یک عنصر را باز می‌گرداند. فقط-خواندنی [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**بازگشت:**
byte