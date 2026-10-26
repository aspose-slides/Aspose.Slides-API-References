---
title: GrayScale
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: نمایانگر یک اثر Gray Scale است.
type: docs
url: /fa/com.aspose.slides/grayscale/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

نمایانگر یک اثر Gray Scale است. تمام مقادیر رنگ اثر را به یک سایه خاکستری که متناسب با روشنایی آن‌ها است تبدیل می‌کند. مقادیر آلفای اثر (شفافیت) تحت تأثیر قرار نمی‌گیرند.
## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر Gray Scale را با اعمال وراثت دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [GrayScale](../../com.aspose.slides/grayscale) مشخص‌شده برابر با [GrayScale](../../com.aspose.slides/grayscale) جاری است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

داده‌های مؤثر اثر Gray Scale را با اعمال وراثت دریافت می‌کند.

**بازگشت:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [GrayScale](../../com.aspose.slides/grayscale) مشخص‌شده برابر با [GrayScale](../../com.aspose.slides/grayscale) جاری است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [GrayScale](../../com.aspose.slides/grayscale) برای مقایسه. |

**بازگشت:**
boolean - درست اگر اشیاء برابر باشند؛ در غیر این صورت، نادرست.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء جاری.