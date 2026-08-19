---
title: Blur
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک افکت Blur است که بر کل شکل، از جمله پر آن، اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/blur/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

نمایانگر افکت تاری (Blur) است که بر کل شکل، از جمله پر (fill) آن اعمال می‌شود. تمام کانال‌های رنگ، از جمله آلفا، تحت تأثیر قرار می‌گیرند.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | مقدار یا تنظیم شعاع تاری. |
| [setRadius(double value)](#setRadius-double-) | مقدار یا تنظیم شعاع تاری. |
| [getGrow()](#getGrow--) | تعیین می‌کند آیا مرزهای شی به دلیل تاری بزرگ شوند یا خیر. |
| [setGrow(boolean value)](#setGrow-boolean-) | تعیین می‌کند آیا مرزهای شی به دلیل تاری بزرگ شوند یا خیر. |
| [getEffective()](#getEffective--) | دریافت داده‌های مؤثر افکت Blur با اعمال ارث‌بری. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Blur](../../com.aspose.slides/blur) مشخص‌شده با [Blur](../../com.aspose.slides/blur) فعلی برابر است یا نه. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

مقدار یا تنظیم شعاع تاری. Read/write double.

**Returns:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

مقدار یا تنظیم شعاع تاری. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

تعیین می‌کند آیا مرزهای شی به دلیل تاری بزرگ شوند یا خیر. مقدار true نشان می‌دهد مرزها بزرگ می‌شوند و مقدار false نشان می‌دهد که بزرگ نمی‌شوند. Read/write boolean.

**Returns:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

تعیین می‌کند آیا مرزهای شی به دلیل تاری بزرگ شوند یا خیر. مقدار true نشان می‌دهد مرزها بزرگ می‌شوند و مقدار false نشان می‌دهد که بزرگ نمی‌شوند. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

دریافت داده‌های مؤثر افکت Blur با اعمال ارث‌بری.

**Returns:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - یک [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [Blur](../../com.aspose.slides/blur) مشخص‌شده با [Blur](../../com.aspose.slides/blur) فعلی برابر است یا نه.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) برای مقایسه. |

**Returns:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت، false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**Returns:**
int - یک کد هش برای شیء جاری.