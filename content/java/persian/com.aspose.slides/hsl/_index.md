---
title: HSL
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک اثر Hue/Saturation/Luminance است.
type: docs
url: /fa/com.aspose.slides/hsl/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

نمایانگر یک اثر Hue/Saturation/Luminance است. مقادیر hue، saturation و luminance می‌توانند به نسبت مقدار فعلی خود تنظیم شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر Hue/Saturation/Luminance را با اعمال ارث‌بری دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [HSL](../../com.aspose.slides/hsl) مشخص شده با [HSL](../../com.aspose.slides/hsl) جاری برابر است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

داده‌های مؤثر اثر Hue/Saturation/Luminance را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - یک [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [HSL](../../com.aspose.slides/hsl) مشخص شده با [HSL](../../com.aspose.slides/hsl) جاری برابر است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [HSL](../../com.aspose.slides/hsl) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء جاری.