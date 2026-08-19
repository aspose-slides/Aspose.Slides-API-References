---
title: AlphaBiLevel
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک اثر Alpha Bi-Level است.
type: docs
url: /fa/com.aspose.slides/alphabilevel/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**همه واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect  
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

نمایانگر یک اثر Alpha Bi-Level است. مقادیر Alpha (شفافیت) کمتر از آستانه به 0 (کاملاً شفاف) تغییر می‌یابد و مقادیر Alpha برابر یا بیشتر از آستانه به 100٪ (کاملاً مات) تغییر می‌کند.

## متدها

| متد | توضیح |
| --- | --- |
| [getThreshold()](#getThreshold--) | آستانهٔ اثر را برمی‌گرداند. |
| [setThreshold(float value)](#setThreshold-float-) | آستانهٔ اثر را برمی‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر Alpha Bi-Level را با اعمال ارث‌بری دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [AlphaBiLevel](../../com.aspose.slides/alphabilevel) مشخص‌شده برابر با [AlphaBiLevel](../../com.aspose.slides/alphabilevel) فعلی است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

آستانهٔ اثر را برمی‌گرداند. خواندنی/نوشتنی float.

**بازگرداندن:**  
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

آستانهٔ اثر را برمی‌گرداند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

داده‌های مؤثر اثر Alpha Bi-Level را با اعمال ارث‌بری دریافت می‌کند.

**بازگرداندن:**  
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - یک [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [AlphaBiLevel](../../com.aspose.slides/alphabilevel) مشخص‌شده برابر با [AlphaBiLevel](../../com.aspose.slides/alphabilevel) فعلی است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) برای مقایسه. |

**بازگرداندن:**  
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**بازگرداندن:**  
int - یک کد هش برای شیء فعلی.