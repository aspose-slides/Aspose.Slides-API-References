---
title: ColorReplace
second_title: Aspose.Slides برای Java مرجع API
description: یک اثر جایگزینی رنگ را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/colorreplace/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

یک اثر جایگزینی رنگ را نشان می‌دهد. تمام رنگ‌های اثر به یک رنگ ثابت تغییر می‌یابند. مقادیر آلفا تحت تأثیر قرار نمی‌گیرند.
## متدها

| متد | توضیح |
| --- | --- |
| [getColor()](#getColor--) | قالب رنگی را که جایگزین رنگ هر پیکسل می‌شود، باز می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر جایگزینی رنگ را با ارث‌بری اعمال‌شده دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [ColorReplace](../../com.aspose.slides/colorreplace) مشخص‌شده برابر با [ColorReplace](../../com.aspose.slides/colorreplace) فعلی است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

قالب رنگی را که جایگزین رنگ هر پیکسل می‌شود، باز می‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**باز می‌گردد:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

داده‌های مؤثر اثر جایگزینی رنگ را با ارث‌بری اعمال‌شده دریافت می‌کند.

**باز می‌گردد:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - یک [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**باز می‌گردد:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [ColorReplace](../../com.aspose.slides/colorreplace) مشخص‌شده برابر با [ColorReplace](../../com.aspose.slides/colorreplace) فعلی است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [ColorReplace](../../com.aspose.slides/colorreplace) برای مقایسه. |

**باز می‌گردد:**
boolean - درست اگر اشیاء برابر باشند؛ در غیر این صورت، نادرست.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**باز می‌گردد:**
int - یک کد هش برای شیء فعلی.