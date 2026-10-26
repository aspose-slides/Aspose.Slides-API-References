---
title: ShapeFrame
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر ویژگی‌های قاب‌های شکل.
type: docs
url: /fa/com.aspose.slides/shapeframe/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

نمایانگر ویژگی‌های قاب شکل است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | ویژگی‌های جدید قاب شکل را ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getX()](#getX--) | مختصات X گوشهٔ بالا-چپ یک قاب را باز می‌گرداند. |
| [getY()](#getY--) | مختصات Y گوشهٔ بالا-چپ یک قاب را باز می‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک قاب را باز می‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع یک قاب را باز می‌گرداند. |
| [getRotation()](#getRotation--) | تعداد درجه‌های دوران قاب حول محور z را باز می‌گرداند. |
| [getCenterX()](#getCenterX--) | مختصات X مرکز یک قاب را باز می‌گرداند. |
| [getCenterY()](#getCenterY--) | مختصات Y مرکز یک قاب را باز می‌گرداند. |
| [getFlipH()](#getFlipH--) | تشخیص می‌دهد که آیا یک قاب به صورت افقی وارون شده است یا خیر. |
| [getFlipV()](#getFlipV--) | تشخیص می‌دهد که آیا یک قاب به صورت عمودی وارون شده است یا خیر. |
| [getRectangle()](#getRectangle--) | مختصات یک قاب را باز می‌گرداند. |
| [deepClone()](#deepClone--) | کپی می‌سازد |
| [cloneT()](#cloneT--) | کپی می‌سازد. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | مقداری را باز می‌گرداند که نشان می‌دهد آیا این نمونه برابر با شیء مشخص‌شده است یا خیر. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | مقداری را باز می‌گرداند که نشان می‌دهد آیا این نمونه برابر با شیء مشخص‌شده است یا خیر. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

ویژگی‌های جدید قاب شکل را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X یک قاب. |
| y | float | مختصات Y یک قاب. |
| width | float | عرض یک قاب. |
| height | float | ارتفاع یک قاب. |
| flipH | byte | True اگر یک قاب افقی وارون شده باشد. |
| flipV | byte | True اگر یک قاب عمودی وارون شده باشد. |
| rotationAngle | float | تعداد درجه‌هایی که یک قاب چرخیده است. |
### getX() {#getX--}
```
public final float getX()
```

مختصات X گوشهٔ بالا-چپ یک قاب را باز می‌گرداند. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getY() {#getY--}
```
public final float getY()
```

مختصات Y گوشهٔ بالا-چپ یک قاب را باز می‌گرداند. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

عرض یک قاب را باز می‌گرداند. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

ارتفاع یک قاب را باز می‌گرداند. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

تعداد درجه‌های چرخش یک قاب حول محور z را باز می‌گرداند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

مختصات X مرکز یک قاب را باز می‌گرداند. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

مختصات Y مرکز یک قاب را باز می‌گرداند. فلوّت فقط‌خواندنی.

**بازگشت:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

تشخیص می‌دهد که آیا یک قاب به صورت افقی وارون شده است یا خیر. فقط‌خواندنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

تشخیص می‌دهد که آیا یک قاب به صورت عمودی وارون شده است یا خیر. فقط‌خواندنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

مختصات یک قاب را باز می‌گرداند. java.awt.geom.Rectangle2D.Float فقط‌خواندنی.

**بازگشت:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

کپی می‌سازد

**بازگشت:**
java.lang.Object - قاب شکل کپی‌شده.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

کپی می‌سازد.

**بازگشت:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - قاب شکل کپی‌شده.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**بازگشت:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

مقداری را باز می‌گرداند که نشان می‌دهد آیا این نمونه برابر با شیء مشخص‌شده است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء برای مقایسه با این نمونه. |

**بازگشت:**
boolean - **true** اگر obj یک ShapeFrame که مقدار برابر این نمونه دارد؛ در غیر این صورت **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

مقداری را باز می‌گرداند که نشان می‌دهد آیا این نمونه برابر با شیء مشخص‌شده است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx برای مقایسه با این نمونه. |

**بازگشت:**
boolean - **true** اگر value یک ShapeFrame که مقدار برابر این نمونه دارد؛ در غیر این صورت **false**.