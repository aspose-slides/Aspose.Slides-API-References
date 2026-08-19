---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: نمایندهٔ مرجع استایل اشکال.
type: docs
url: /fa/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

مرجع استایل شکل را نمایش می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | رنگ حاشیهٔ شکل را باز می‌گرداند. |
| [getLineStyleIndex()](#getLineStyleIndex--) | اندیس ستون خط را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | اندیس ستون خط را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [getFillColor()](#getFillColor--) | رنگ پرکنندهٔ شکل را باز می‌گرداند. |
| [getFillStyleIndex()](#getFillStyleIndex--) | اندیس ستون پرکنندهٔ شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | اندیس ستون پرکنندهٔ شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. |
| [getEffectColor()](#getEffectColor--) | رنگ افکت شکل را باز می‌گرداند. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | اندیس ستون افکت شکل را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | اندیس ستون افکت شکل را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. |
| [getFontColor()](#getFontColor--) | رنگ فونت شکل را باز می‌گرداند. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | اندیس فونت شکل را در مجموعهٔ فونت‌ها باز می‌گرداند یا تنظیم می‌کند. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | اندیس فونت شکل را در مجموعهٔ فونت‌ها باز می‌گرداند یا تنظیم می‌کند. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

رنگ حاشیهٔ شکل را باز می‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

اندیس ستون خط را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌و-نوشته int.

**بازگشت:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

اندیس ستون خط را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌و-نوشته int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

رنگ پرکنندهٔ شکل را باز می‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

اندیس ستون پرکنندهٔ شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. مقدار ۰ یعنی بدون پرکردن، مقدار مثبت – اندیس در استایل‌های پرکنندهٔ تم، مقدار منفی – اندیس در استایل‌های پس‌زمینهٔ تم. قابل‌خواندن‌و-نوشته short.

**بازگشت:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

اندیس ستون پرکنندهٔ شکل را در ماتریس‌های استایل باز می‌گرداند یا تنظیم می‌کند. مقدار ۰ یعنی بدون پرکردن، مقدار مثبت – اندیس در استایل‌های پرکنندهٔ تم، مقدار منفی – اندیس در استایل‌های پس‌زمینهٔ تم. قابل‌خواندن‌و-نوشته short.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

رنگ افکت شکل را باز می‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

اندیس ستون افکت شکل را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌و-نوشته long.

**بازگشت:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

اندیس ستون افکت شکل را در یک ماتریس استایل باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌و-نوشته long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

رنگ فونت شکل را باز می‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

اندیس فونت شکل را در مجموعهٔ فونت‌ها باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌و-نوشته [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**بازگشت:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

اندیس فونت شکل را در مجموعهٔ فونت‌ها باز می‌گرداند یا تنظیم می‌کند. قابل‌خواندن‌و-نوشته [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |