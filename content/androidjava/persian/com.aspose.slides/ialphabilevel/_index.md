---
title: IAlphaBiLevel
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر دو سطحی آلفا است.
type: docs
url: /fa/com.aspose.slides/ialphabilevel/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

یک اثر دو سطحی آلفا را نشان می‌دهد. مقادیر آلفا (شفافیت) کمتر از آستانه به 0 (کاملاً شفاف) تغییر می‌یابند و مقادیر آلفا بزرگ‌تر یا مساوی آستانه به 100٪ (کاملاً مات) تغییر می‌یابند.

--------------------

از ImageTransformOperationFactory برای ایجاد نمونه‌ها در COM استفاده کنید.
## Methods

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | آستانه اثر را برمی‌گرداند. |
| [setThreshold(float value)](#setThreshold-float-) | آستانه اثر را برمی‌گرداند. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

آستانه اثر را برمی‌گرداند. قابل خواندن/قابل نوشتن float.

**بازگشت:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

آستانه اثر را برمی‌گرداند. قابل خواندن/قابل نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |