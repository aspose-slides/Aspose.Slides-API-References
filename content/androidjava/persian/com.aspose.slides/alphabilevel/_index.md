---
title: AlphaBiLevel
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک اثر آلفا دو-سطحی را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/alphabilevel/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect  
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

یک اثر آلفا دو-سطحی را نشان می‌دهد. مقادیر آلفا (Opacity) کمتر از آستانه به 0 (کاملاً شفاف) تغییر می‌یابند و مقادیر آلفا بزرگتر یا مساوی آستانه به 100٪ (کاملاً مات) تغییر می‌شوند.

## Methods

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | آستانه اثر را برمی‌گرداند. |
| [setThreshold(float value)](#setThreshold-float-) | آستانه اثر را برمی‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر آلفا دو-سطحی را با درنظر گرفتن وراثت دریافت می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [AlphaBiLevel](../../com.aspose.slides/alphabilevel) مشخص شده با [AlphaBiLevel](../../com.aspose.slides/alphabilevel) فعلی برابر است یا نه. |
| [hashCode()](#hashCode--) | به‌عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

آستانه اثر را برمی‌گرداند. خواندنی/نوشتنی float.

**Returns:**  
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

آستانه اثر را برمی‌گرداند. خواندنی/نوشتنی float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

داده‌های مؤثر اثر آلفا دو-سطحی را با درنظر گرفتن وراثت دریافت می‌کند.

**Returns:**  
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند آیا [AlphaBiLevel](../../com.aspose.slides/alphabilevel) مشخص شده با [AlphaBiLevel](../../com.aspose.slides/alphabilevel) فعلی برابر است یا نه.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaBiLevel](../../com.aspose.slides/alphabilevel) to compare. |

**Returns:**  
boolean - اگر اشیاء برابر باشند true؛ در غیر این صورت false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

به‌عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**Returns:**  
int - A hash code for the current object.