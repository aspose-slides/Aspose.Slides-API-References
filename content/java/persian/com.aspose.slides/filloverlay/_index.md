---
title: FillOverlay
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک اثر Fill Overlay.
type: docs
url: /fa/com.aspose.slides/filloverlay/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect  
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

نماده‌ای از اثر Fill Overlay را نشان می‌دهد. یک Fill Overlay ممکن است برای تعیین پر کردن اضافی برای یک شیء و ترکیب دو پر کردن با هم استفاده شود.

## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | فرمت پر. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | داده‌های مؤثر Fill Overlay را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [FillOverlay](../../com.aspose.slides/filloverlay) مشخص‌شده برابر با [FillOverlay](../../com.aspose.slides/filloverlay) فعلی است یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

فرمت پر. فقط خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**باز می‌گرداند:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. قابل نوشتن [FillBlendMode](../../com.aspose.slides/fillblendmode).

**باز می‌گرداند:**  
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. قابل نوشتن [FillBlendMode](../../com.aspose.slides/fillblendmode).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

داده‌های مؤثر Fill Overlay را با اعمال ارث‌بری دریافت می‌کند.

**باز می‌گرداند:**  
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - یک [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**باز می‌گرداند:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [FillOverlay](../../com.aspose.slides/filloverlay) مشخص‌شده برابر با [FillOverlay](../../com.aspose.slides/filloverlay) فعلی است یا خیر.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) برای مقایسه. |

**باز می‌گرداند:**  
boolean - true اگر اشیا برابر باشند؛ در غیر این صورت false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**باز می‌گرداند:**  
int - یک کد هش برای شیٔ فعلی.