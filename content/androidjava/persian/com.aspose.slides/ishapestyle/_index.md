---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: نمایش ارجاع سبک اشکال.
type: docs
url: /fa/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

نمایش ارجاع سبک شکل.
## متدها

| متد | توصیف |
| --- | --- |
| [getLineColor()](#getLineColor--) | رنگ خط بیرونی شکل را برمی‌گرداند. |
| [getLineStyleIndex()](#getLineStyleIndex--) | ایندکس ستونی خط را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | ایندکس ستونی خط را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. |
| [getFillColor()](#getFillColor--) | رنگ پر شدن شکل را برمی‌گرداند. |
| [getFillStyleIndex()](#getFillStyleIndex--) | ایندکس ستونی پر شدن شکل را در ماتریس‌های سبک برمی‌گرداند یا تنظیم می‌کند. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | ایندکس ستونی پر شدن شکل را در ماتریس‌های سبک برمی‌گرداند یا تنظیم می‌کند. |
| [getEffectColor()](#getEffectColor--) | رنگ اثر شکل را برمی‌گرداند. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | ایندکس ستونی اثر شکل را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | ایندکس ستونی اثر شکل را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. |
| [getFontColor()](#getFontColor--) | رنگ فونت شکل را برمی‌گرداند. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | ایندکس فونت شکل را در مجموعه فونت‌ها برمی‌گرداند یا تنظیم می‌کند. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | ایندکس فونت شکل را در مجموعه فونت‌ها برمی‌گرداند یا تنظیم می‌کند. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

رنگ خط بیرونی شکل را برمی‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

ایندکس ستونی خط را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**بازگشت:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

ایندکس ستونی خط را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

رنگ پر شدن شکل را برمی‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

ایندکس ستونی پر شدن شکل را در ماتریس‌های سبک برمی‌گرداند یا تنظیم می‌کند. 0 به معنای عدم پر شدن، مقدار مثبت - ایندکس در سبک‌های پر شدن تم، مقدار منفی - ایندکس در سبک‌های پس‌زمینه تم. خواندن/نوشتن short.

**بازگشت:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

ایندکس ستونی پر شدن شکل را در ماتریس‌های سبک برمی‌گرداند یا تنظیم می‌کند. 0 به معنای عدم پر شدن، مقدار مثبت - ایندکس در سبک‌های پر شدن تم، مقدار منفی - ایندکس در سبک‌های پس‌زمینه تم. خواندن/نوشتن short.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

رنگ اثر شکل را برمی‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

ایندکس ستونی اثر شکل را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن long.

**بازگشت:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

ایندکس ستونی اثر شکل را در ماتریس سبک برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

رنگ فونت شکل را برمی‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

ایندکس فونت شکل را در مجموعه فونت‌ها برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**بازگشت:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

ایندکس فونت شکل را در مجموعه فونت‌ها برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |