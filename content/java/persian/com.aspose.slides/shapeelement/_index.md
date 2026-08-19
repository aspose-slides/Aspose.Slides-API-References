---
title: ShapeElement
second_title: مرجع API Aspose.Slides برای جاوا
description: بخشی از شکل با همان ویژگی‌های مرز و پر کردن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/shapeelement/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

نمایانگر بخشی از شکل با ویژگی‌های همان حاشیه و پر کردن است.
## متدها

| Method | Description |
| --- | --- |
| [getParentShape()](#getParentShape--) | یک Shape_PPT را برمی‌گرداند که عنصر برای آن ایجاد شده است. |
| [getPathPoints()](#getPathPoints--) | آرایه‌ای از نقاط را که شکل‌جغرافیای مسیر عنصر را تعریف می‌کند، برمی‌گرداند. |
| [getPathTypes()](#getPathTypes--) | آرایه‌ای از مقادیر بایت را که نوع هر نقطه در مسیر عنصر را مشخص می‌کند، برمی‌گرداند. |
| [getFillSource()](#getFillSource--) | اطلاعاتی در مورد نحوه پر کردن یک عنصر برمی‌گرداند. |
| [getStrokeSource()](#getStrokeSource--) | اطلاعاتی در مورد نحوه خط‌کشی یک عنصر برمی‌گرداند. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

یک Shape_PPT را برمی‌گرداند که عنصر برای آن ایجاد شده است. فقط-خواندنی [Shape](../../com.aspose.slides/shape).

**مقدار بازگشت:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

آرایه‌ای از نقاط را که شکل‌جغرافیای مسیر عنصر را تعریف می‌کند، برمی‌گرداند.

**مقدار بازگشت:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

آرایه‌ای از مقادیر بایت را که نوع هر نقطه در مسیر عنصر را مشخص می‌کند، برمی‌گرداند.

**0** نشان می‌دهد که نقطه شروع یک شکل است.

**1** نشان می‌دهد که نقطه یکی از دو انتهای یک خط است.

**3** نشان می‌دهد که نقطه یک انتها یا نقطهٔ کنترل یک اسپلین بزیهٔ مکعبی است.

**7** تمام بیت‌ها را به جز سه بیت کم‌ارزش که نوع نقطه را نشان می‌دهند، ماسک می‌کند.

**16** مشخص می‌‌کند که بخش متناظر خط‌چین است.

**32** مشخص می‌کند که نقطه یک نشانگر است.

**128** مشخص می‌کند که نقطه آخرین نقطه در یک زیرمسیر بسته (شکل) است.

**129** نشان می‌دهد که نقطه داده هم انتهای یک بخش خط است و هم آخرین نقطه یک زیرمسیر بسته.

**مقدار بازگشت:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

اطلاعاتی در مورد نحوه پر کردن یک عنصر برمی‌گرداند. فقط-خواندنی [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**مقدار بازگشت:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

اطلاعاتی در مورد نحوه خط‌کشی یک عنصر برمی‌گرداند. فقط-خواندنی [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**مقدار بازگشت:**
byte