---
title: Duotone
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش یک اثر دو-رنگ.
type: docs
url: /fa/com.aspose.slides/duotone/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

نمایش یک اثر دو-رنگ. برای هر پیکسل، Color1 و Color2 را از طریق یک درون‌یابی خطی ترکیب می‌کند تا رنگ جدید آن پیکسل تعیین شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getColor1()](#getColor1--) | قالب رنگ هدف را برای پیکسل‌های تاریک برمی‌گرداند. |
| [getColor2()](#getColor2--) | قالب رنگ هدف را برای پیکسل‌های روشن برمی‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر دو-رنگ را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Duotone](../../com.aspose.slides/duotone) مشخص شده با [Duotone](../../com.aspose.slides/duotone) جاری برابر است یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


قالب رنگ هدف را برای پیکسل‌های تاریک برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


قالب رنگ هدف را برای پیکسل‌های روشن برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


داده‌های مؤثر اثر دو-رنگ را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - یک [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


نسخه. فقط‌خواندنی long.

**بازگشت:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تعیین می‌کند آیا [Duotone](../../com.aspose.slides/duotone) مشخص شده با [Duotone](../../com.aspose.slides/duotone) جاری برابر است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) برای مقایسه. |

**بازگشت:**
boolean - اگر اشیاء برابر هستند، true؛ در غیر این صورت false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء جاری.