---
title: Duotone
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک اثر Duotone.
type: docs
url: /fa/com.aspose.slides/duotone/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

نمایانگر یک اثر Duotone است. برای هر پیکسل، Color1 و Color2 را از طریق یک درون‌یابی خطی ترکیب می‌کند تا رنگ جدید آن پیکسل تعیین شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getColor1()](#getColor1--) | قالب رنگ هدف را برای پیکسل‌های تاریک بر می‌گرداند. |
| [getColor2()](#getColor2--) | قالب رنگ هدف را برای پیکسل‌های روشن بر می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر Duotone را با اعمال وراثت دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Duotone](../../com.aspose.slides/duotone) مشخص شده برابر با [Duotone](../../com.aspose.slides/duotone) فعلی است. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

قالب رنگ هدف را برای پیکسل‌های تاریک بر می‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

قالب رنگ هدف را برای پیکسل‌های روشن بر می‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

داده‌های مؤثر اثر Duotone را با اعمال وراثت دریافت می‌کند.

**بازگشت:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - یک [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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

تعیین می‌کند آیا [Duotone](../../com.aspose.slides/duotone) مشخص‌شده برابر با [Duotone](../../com.aspose.slides/duotone) فعلی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر هستند؛ در غیر این صورت، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء فعلی.