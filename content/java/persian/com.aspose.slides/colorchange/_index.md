---
title: ColorChange
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک اثر تغییر رنگ است.
type: docs
url: /fa/com.aspose.slides/colorchange/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor.

## متدها

| متد | توضیح |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color که جایگزین خواهد شد. |
| [getToColor()](#getToColor--) | Color که جایگزین می‌کند. |
| [getEffective()](#getEffective--) | داده‌های موثر Color Change را با اعمال ارث‌برداری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [ColorChange](../../com.aspose.slides/colorchange) مشخص شده با [ColorChange](../../com.aspose.slides/colorchange) جاری برابر است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Color که جایگزین خواهد شد. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگرداندن:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Color که جایگزین می‌کند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگرداندن:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

داده‌های موثر Color Change را با اعمال ارث‌برداری دریافت می‌کند.

**بازگرداندن:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - یک [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگرداندن:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [ColorChange](../../com.aspose.slides/colorchange) مشخص شده با [ColorChange](../../com.aspose.slides/colorchange) جاری برابر است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) برای مقایسه. |

**بازگرداندن:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگرداندن:**
int - یک مقدار هش برای شیء فعلی.