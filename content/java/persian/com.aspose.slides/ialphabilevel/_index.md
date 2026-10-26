---
title: IAlphaBiLevel
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک اثر Alpha Bi-Level است.
type: docs
url: /fa/com.aspose.slides/ialphabilevel/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

نمایش یک اثر Alpha Bi-Level. مقادیر Alpha (Opacity) که کمتر از آستانه هستند به 0 (کاملاً شفاف) تغییر می‌یابند و مقادیر alpha که بزرگ‌تر یا مساوی آستانه هستند به 100٪ (کاملاً مات) تغییر می‌کنند.

--------------------

از ImageTransformOperationFactory برای ایجاد نمونه‌ها در COM استفاده کنید.
## متدها

| متد | توضیح |
| --- | --- |
| [getThreshold()](#getThreshold--) | آستانه اثر را برمی‌گرداند. |
| [setThreshold(float value)](#setThreshold-float-) | آستانه اثر را برمی‌گرداند. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

آستانه اثر را برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن float.

**بازگشت:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

آستانه اثر را برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |