---
title: ColorReplace
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر جایگزینی رنگ است.
type: docs
url: /fa/com.aspose.slides/colorreplace/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable  
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

نمایش یک اثر جایگزینی رنگ. تمام رنگ‌های اثر به یک رنگ ثابت تغییر می‌کنند. مقادیر آلفا تحت تأثیر قرار نمی‌گیرند.

## متدها

| متد | توضیح |
| --- | --- |
| [getColor()](#getColor--) | قالب رنگی را برمی‌گرداند که رنگ هر پیکسل را جایگزین می‌کند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر جایگزینی رنگ را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تشخیص می‌دهد آیا [ColorReplace](../../com.aspose.slides/colorreplace) مشخص شده برابر با [ColorReplace](../../com.aspose.slides/colorreplace) فعلی است. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

قالب رنگی را برمی‌گرداند که رنگ هر پیکسل را جایگزین می‌کند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

داده‌های مؤثر اثر جایگزینی رنگ را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**  
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - یک [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).

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

تشخیص می‌دهد آیا [ColorReplace](../../com.aspose.slides/colorreplace) مشخص شده برابر با [ColorReplace](../../com.aspose.slides/colorreplace) فعلی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [ColorReplace](../../com.aspose.slides/colorreplace) برای مقایسه. |

**بازگشت:**  
boolean - درست اگر اشیاء برابر باشند؛ در غیر این صورت، نادرست.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**  
int - یک کد هش برای شیء فعلی.