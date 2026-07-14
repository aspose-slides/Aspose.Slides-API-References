---
title: FillOverlay
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک افکت Fill Overlay است.
type: docs
url: /fa/com.aspose.slides/filloverlay/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Represents a Fill Overlay effect. A Fill Overlay may be used to specify an additional fill for an object and blend the two fills together.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر Fill Overlay را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [FillOverlay](../../com.aspose.slides/filloverlay) مشخص‌شده برابر با [FillOverlay](../../com.aspose.slides/filloverlay) جاری است یا خیر. |
| [hashCode()](#hashCode--) | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fill format. فقط خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. قابل خواندن/نوشتن [FillBlendMode](../../com.aspose.slides/fillblendmode).

**بازگشت:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. قابل خواندن/نوشتن [FillBlendMode](../../com.aspose.slides/fillblendmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

داده‌های مؤثر اثر Fill Overlay را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - یک [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. فقط خواندنی long.

**بازگشت:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [FillOverlay](../../com.aspose.slides/filloverlay) مشخص‌شده برابر با [FillOverlay](../../com.aspose.slides/filloverlay) جاری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) برای مقایسه. |

**بازگشت:**
boolean - صحیح اگر اشیاء برابر باشند؛ در غیر این صورت، غلط.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شیء جاری.