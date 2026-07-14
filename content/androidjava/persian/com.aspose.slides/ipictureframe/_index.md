---
title: IPictureFrame
second_title: مرجع API جاوا برای Aspose.Slides در Android
description: یک فریم حاوی تصویر داخل آن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ipictureframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

نمایانگر یک فریم حاوی یک تصویر است.
## متدها

| متد | توضیح |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | قفل‌های PictureFrame را برمی‌گرداند. |
| [getPictureFormat()](#getPictureFormat--) | شیء PictureFillFormat را برای یک فریم تصویری برمی‌گرداند. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | مقیاس عرض (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | مقیاس عرض (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

قفل‌های PictureFrame را برمی‌گرداند. فقط-خواندنی [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**بازگشت:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

شیء PictureFillFormat را برای یک فریم تصویری برمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. float خواندن/نوشتن.

**بازگشت:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. float خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

مقیاس عرض (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. float خواندن/نوشتن.

**بازگشت:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

مقیاس عرض (نسبت به اندازه اصلی تصویر) فریم تصویری را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. float خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |