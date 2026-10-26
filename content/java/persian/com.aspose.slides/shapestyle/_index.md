---
title: ShapeStyle
second_title: مرجع API Aspose.Slides برای جاوا
description: نماینده مرجع استایل اشکال.
type: docs
url: /fa/com.aspose.slides/shapestyle/
---
**وراثت:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)  
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

نمایانگر مرجع استایل شکل.

## متدها

| متد | توضیح |
| --- | --- |
| [getLineColor()](#getLineColor--) | مقدار رنگ خطوط پیرامون یک شکل را باز می‌گرداند. |
| [getLineStyleIndex()](#getLineStyleIndex--) | ایندکس ستون خط را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | ایندکس ستون خط را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [getFillColor()](#getFillColor--) | مقدار رنگ پرکردن یک شکل را باز می‌گرداند. |
| [getFillStyleIndex()](#getFillStyleIndex--) | ایندکس ستون پرکردن شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | ایندکس ستون پرکردن شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. |
| [getEffectColor()](#getEffectColor--) | مقدار رنگ افکت یک شکل را باز می‌گرداند. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | ایندکس ستون افکت شکل را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | ایندکس ستون افکت شکل را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [getFontColor()](#getFontColor--) | مقدار رنگ فونت یک شکل را باز می‌گرداند. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | ایندکس فونت شکل را در مجموعه فونت‌ها باز می‌گرداند یا تنظیم می‌کند. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | ایندکس فونت شکل را در مجموعه فونت‌ها باز می‌گرداند یا تنظیم می‌کند. |

### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

باز می‌گرداند رنگ خطوط پیرامون یک شکل. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

ایندکس ستون خط را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**بازگشت:**  
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

ایندکس ستون خط را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

باز می‌گرداند رنگ پرکردن یک شکل. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

ایندکس ستون پرکردن شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنای بدون پرکردن است، مقدار مثبت → ایندکس در استایل‌های پرکردن تم، مقدار منفی → ایندکس در استایل‌های پس‌زمینه تم. قابل‌خواندن/نوشتن short.

**بازگشت:**  
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

ایندکس ستون پرکردن شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. مقدار 0 به معنای بدون پرکردن است، مقدار مثبت → ایندکس در استایل‌های پرکردن تم، مقدار منفی → ایندکس در استایل‌های پس‌زمینه تم. قابل‌خواندن/نوشتن short.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

باز می‌گرداند رنگ افکت یک شکل. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

ایندکس ستون افکت شکل را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن long.

**بازگشت:**  
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

ایندکس ستون افکت شکل را در ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن long.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

باز می‌گرداند رنگ فونت یک شکل. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

ایندکس فونت شکل را در مجموعه فونت‌ها باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**بازگشت:**  
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

ایندکس فونت شکل را در مجموعه فونت‌ها باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |