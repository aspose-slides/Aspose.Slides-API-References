---
title: ColorChange
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: یک اثر تغییر رنگ را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/colorchange/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

نمایش یک اثر تغییر رنگ. نمونه‌های FromColor با نمونه‌های ToColor جایگزین می‌شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFromColor()](#getFromColor--) | رنگی که جایگزین خواهد شد. |
| [getToColor()](#getToColor--) | رنگی که جایگزین خواهد کرد. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر تغییر رنگ را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تشخیص می‌دهد آیا [ColorChange](../../com.aspose.slides/colorchange) مشخص شده برابر با [ColorChange](../../com.aspose.slides/colorchange) فعلی است. |
| [hashCode()](#hashCode--) | به‌عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

رنگی که جایگزین خواهد شد. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

رنگی که جایگزین خواهد کرد. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

داده‌های مؤثر اثر تغییر رنگ را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - یک [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تشخیص می‌دهد آیا [ColorChange](../../com.aspose.slides/colorchange) مشخص شده برابر با [ColorChange](../../com.aspose.slides/colorchange) فعلی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) برای مقایسه. |

**بازگشت:**
boolean - درست اگر اشیاء برابر باشند؛ در غیر این صورت، نادرست.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء فعلی.