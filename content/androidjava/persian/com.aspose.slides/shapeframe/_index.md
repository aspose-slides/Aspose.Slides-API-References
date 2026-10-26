---
title: ShapeFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: خواص قاب‌های شکل را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/shapeframe/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)  
```
public class ShapeFrame implements IShapeFrame
```

خواص قاب شکل را نمایش می‌دهد.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | یک شیء جدید از خواص قاب شکل ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getX()](#getX--) | مختصات X گوشهٔ بالا-چپ یک قاب را برمی‌گرداند. |
| [getY()](#getY--) | مختصات Y گوشهٔ بالا-چپ یک قاب را برمی‌گرداند. |
| [getWidth()](#getWidth--) | عرض یک قاب را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع یک قاب را برمی‌گرداند. |
| [getRotation()](#getRotation--) | تعداد درجاتی که یک قاب حول محور Z چرخیده است را برمی‌گرداند. |
| [getCenterX()](#getCenterX--) | مختصات X مرکز یک قاب را برمی‌گرداند. |
| [getCenterY()](#getCenterY--) | مختصات Y مرکز یک قاب را برمی‌گرداند. |
| [getFlipH()](#getFlipH--) | تعیین می‌کند آیا یک قاب به صورت افقی معکوس شده است یا نه. |
| [getFlipV()](#getFlipV--) | تعیین می‌کند آیا یک قاب به صورت عمودی معکوس شده است یا نه. |
| [getRectangle()](#getRectangle--) | مختصات یک قاب را برمی‌گرداند. |
| [deepClone()](#deepClone--) | کپی می‌کند |
| [cloneT()](#cloneT--) | کپی می‌کند. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | مقداری را برمی‌گرداند که نشان می‌دهد آیا این نمونه برابر با یک شیء مشخص است یا خیر. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | مقداری را برمی‌گرداند که نشان می‌دهد آیا این نمونه برابر با یک شیء مشخص است یا خیر. |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

خواص جدیدی برای قاب شکل ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X یک قاب. |
| y | float | مختصات Y یک قاب. |
| width | float | عرض یک قاب. |
| height | float | ارتفاع یک قاب. |
| flipH | byte | درست اگر قاب به صورت افقی معکوس شده باشد. |
| flipV | byte | درست اگر قاب به صورت عمودی معکوس شده باشد. |
| rotationAngle | float | تعداد درجاتی که یک قاب چرخیده است. |

### getX() {#getX--}
```
public final float getX()
```

مختصات X گوشهٔ بالا-چپ یک قاب را برمی‌گرداند. فقط-خواندنی float.

**برگشت:**  
float

### getY() {#getY--}
```
public final float getY()
```

مختصات Y گوشهٔ بالا-چپ یک قاب را برمی‌گرداند. فقط-خواندنی float.

**برگشت:**  
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

عرض یک قاب را برمی‌گرداند. فقط-خواندنی float.

**برگشت:**  
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

ارتفاع یک قاب را برمی‌گرداند. فقط-خواندنی float.

**برگشت:**  
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

تعداد درجاتی که یک قاب حول محور Z چرخیده است را برمی‌گرداند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. فقط-خواندنی float.

**برگشت:**  
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

مختصات X مرکز یک قاب را برمی‌گرداند. فقط-خواندنی float.

**برگشت:**  
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

مختصات Y مرکز یک قاب را برمی‌گرداند. فقط-خواندنی float.

**برگشت:**  
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

تعیین می‌کند آیا یک قاب به صورت افقی معکوس شده است یا نه. فقط-خواندنی [NullableBool](../../com.aspose.slides/nullablebool).

**برگشت:**  
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

تعیین می‌کند آیا یک قاب به صورت عمودی معکوس شده است یا نه. فقط-خواندنی [NullableBool](../../com.aspose.slides/nullablebool).

**برگشت:**  
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

مختصات یک قاب را برمی‌گرداند. فقط-خواندنی android.graphics.RectF.

**برگشت:**  
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

کپی می‌کند

**برگشت:**  
java.lang.Object - قاب شکل کپی‌شده.

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

کپی می‌کند.

**برگشت:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe) - قاب شکل کپی‌شده.

### hashCode() {#hashCode--}
```
public int hashCode()
```

**برگشت:**  
int

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا این نمونه برابر با یک شیء مشخص است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء‌ای که با این نمونه مقایسه می‌شود. |

**برگشت:**  
boolean - **true** اگر obj یک ShapeFrame باشد که همان مقدار را دارد؛ در غیر این صورت **false**.

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا این نمونه برابر با یک شیء مشخص است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | شیء ShapeFRameEx ای که با این نمونه مقایسه می‌شود. |

**برگشت:**  
boolean - **true** اگر value یک ShapeFrame باشد که همان مقدار را دارد؛ در غیر این صورت **false**.