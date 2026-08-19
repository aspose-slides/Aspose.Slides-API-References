---
title: BiLevel
second_title: Aspose.Slides برای Java مرجع API
description: یک افکت دو-سطحه سیاه/سفید را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/bilevel/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

نقش یک افکت دو-سطحه (سیاه/سفید) را دارد. رنگ‌های ورودی که روشنایی آن‌ها کمتر از مقدار آستانهٔ مشخص شده است به سیاه تغییر می‌یابند. رنگ‌های ورودی که روشنایی آن‌ها برابر یا بزرگتر از مقدار مشخص شده است به سفید تنظیم می‌شوند. مقادیر افکت آلفا تحت این افکت تغییر نمی‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | داده‌های افکت دو-سطحهٔ مؤثر را با اعمال ارث‌بری دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [BiLevel](../../com.aspose.slides/bilevel) مشخص شده برابر با [BiLevel](../../com.aspose.slides/bilevel) فعلی است یا نه. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


داده‌های افکت دو-سطحهٔ مؤثر را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تعیین می‌کند آیا [BiLevel](../../com.aspose.slides/bilevel) مشخص شده برابر با [BiLevel](../../com.aspose.slides/bilevel) فعلی است یا نه.

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
int - یک کد هش برای شیء فعلی.