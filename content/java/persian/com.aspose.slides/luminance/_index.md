---
title: Luminance
second_title: مرجع API Aspose.Slides برای جاوا
description: یک اثر روشنایی را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/luminance/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام واسط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

یک اثر روشنایی را نشان می‌دهد. روشنایی به‌صورت خطی تمام رنگ‌ها را به سمت سفید یا سیاه نزدیک‌تر می‌کند. کنتراست تمام رنگ‌ها را طوری مقیاس می‌دهد که یا نزدیک‌تر یا دورتر از هم شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | دیتای مؤثر اثر روشنایی را با اعمال ارث‌بری دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Luminance](../../com.aspose.slides/luminance) مشخص شده با [Luminance](../../com.aspose.slides/luminance) جاری برابر است یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای نوع خاصی عمل می‌کند. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


دیتای مؤثر اثر روشنایی را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - یک [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تعیین می‌کند آیا [Luminance](../../com.aspose.slides/luminance) مشخص شده با [Luminance](../../com.aspose.slides/luminance) جاری برابر است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [Luminance](../../com.aspose.slides/luminance) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


به‌عنوان تابع هش برای نوع خاصی عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء جاری.