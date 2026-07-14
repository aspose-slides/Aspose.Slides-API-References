---
title: Blur
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر Blur است که بر روی تمام شکل، از جمله fill آن، اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/blur/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

نمایانگر یک اثر Blur است که بر روی کل شکل، از جمله fill آن اعمال می‌شود. تمام کانال‌های رنگ، از جمله alpha، تحت تأثیر قرار می‌گیرند.

## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | مقدار شعاع تاری را برمی‌گرداند یا تنظیم می‌کند. |
| [setRadius(double value)](#setRadius-double-) | مقدار شعاع تاری را برمی‌گرداند یا تنظیم می‌کند. |
| [getGrow()](#getGrow--) | تعیین می‌کند آیا مرزهای شی به علت تاری بزرگ شوند یا نه. |
| [setGrow(boolean value)](#setGrow-boolean-) | تعیین می‌کند آیا مرزهای شی به علت تاری بزرگ شوند یا نه. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر Blur را با اعمال ارث‌بری دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Blur](../../com.aspose.slides/blur) مشخص شده برابر با [Blur](../../com.aspose.slides/blur) جاری است یا خیر. |
| [hashCode()](#hashCode--) | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

مقدار شعاع تاری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

مقدار شعاع تاری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

تعیین می‌کند آیا مرزهای شی به علت تاری بزرگ شوند یا نه. مقدار true نشان می‌دهد مرزها بزرگ می‌شوند و false نشان می‌دهد که بزرگ نمی‌شوند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

تعیین می‌کند آیا مرزهای شی به علت تاری بزرگ شوند یا نه. مقدار true نشان می‌دهد مرزها بزرگ می‌شوند و false نشان می‌دهد که بزرگ نمی‌شوند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

داده‌های مؤثر اثر Blur را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - یک [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [Blur](../../com.aspose.slides/blur) مشخص شده برابر با [Blur](../../com.aspose.slides/blur) جاری است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت، false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شی جاری.