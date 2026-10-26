---
title: BiLevel
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر دو-سطحی سیاه/سفید است.
type: docs
url: /fa/com.aspose.slides/bilevel/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام اینترفیس‌های پیاده‌سازی شده:**  
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect  
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

نمایانگر یک اثر دو-سطحی (سیاه/سفید) است. رنگ‌های ورودی که روشنایی آن‌ها کمتر از مقدار آستانه مشخص شده باشد به رنگ سیاه تغییر می‌یابند. رنگ‌های ورودی که روشنایی آن‌ها برابر یا بیشتر از مقدار مشخص شده باشد به سفید تنظیم می‌شوند. مقادیر اثر آلفا تحت این اثر تغییری نمی‌کنند.

## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر دو-سطحی را با اعمال ارث‌بری دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تشخیص می‌دهد آیا [BiLevel](../../com.aspose.slides/bilevel) مشخص شده با [BiLevel](../../com.aspose.slides/bilevel) جاری برابر است یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

داده‌های مؤثر اثر دو-سطحی را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**  
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - یک [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تشخیص می‌دهد آیا [BiLevel](../../com.aspose.slides/bilevel) مشخص شده با [BiLevel](../../com.aspose.slides/bilevel) جاری برابر است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) برای مقایسه. |

**بازگشت:**  
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**  
int - یک کد هش برای شیء جاری.