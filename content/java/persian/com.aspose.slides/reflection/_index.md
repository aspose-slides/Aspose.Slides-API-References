---
title: Reflection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک اثر انعکاس است.
type: docs
url: /fa/com.aspose.slides/reflection/
---
**ارث‌بری:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

نمایانگر اثر انعکاس است.
## متدها

| متد | توضیح |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | موقعیت شروع (در طول شیب‌دار گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | موقعیت شروع (در طول شیب‌دار گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. |
| [getEndPosAlpha()](#getEndPosAlpha--) | موقعیت انتها (در طول شیب‌دار گرادیان آلفا) مقدار آلفای انتها (درصد) را مشخص می‌کند. |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | موقعیت انتها (در طول شیب‌دار گرادیان آلفا) مقدار آلفای انتها (درصد) را مشخص می‌کند. |
| [getFadeDirection()](#getFadeDirection--) | جهت جابجایی انعکاس را مشخص می‌کند. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | جهت جابجایی انعکاس را مشخص می‌کند. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | شفافیت شروع انعکاس. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | شفافیت شروع انعکاس. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | شفافیت انتهای انعکاس. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | شفافیت انتهای انعکاس. |
| [getBlurRadius()](#getBlurRadius--) | شعاع تاری. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | شعاع تاری. |
| [getDirection()](#getDirection--) | جهت انعکاس. |
| [setDirection(float value)](#setDirection-float-) | جهت انعکاس. |
| [getDistance()](#getDistance--) | فاصله انعکاس. |
| [setDistance(double value)](#setDistance-double-) | فاصله انعکاس. |
| [getRectangleAlign()](#getRectangleAlign--) | ترازبندی مستطیل. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | ترازبندی مستطیل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | زاویهٔ کج‌کردن افقی را مشخص می‌کند. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | زاویهٔ کج‌کردن افقی را مشخص می‌کند. |
| [getSkewVertical()](#getSkewVertical--) | زاویهٔ کج‌کردن عمودی را مشخص می‌کند. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | زاویهٔ کج‌کردن عمودی را مشخص می‌کند. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | مشخص می‌کند که آیا انعکاس باید همراه با شکل چرخانده شود اگر شکل چرخانده شود. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | مشخص می‌کند که آیا انعکاس باید همراه با شکل چرخانده شود اگر شکل چرخانده شود. |
| [getScaleHorizontal()](#getScaleHorizontal--) | عامل مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | عامل مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) |
| [getScaleVertical()](#getScaleVertical--) | عامل مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) |
| [setScaleVertical(double value)](#setScaleVertical-double-) | عامل مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) |
| [getEffective()](#getEffective--) | داده‌های مؤثر اثر انعکاس را با اعمال ارث‌بری دریافت می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند آیا [Reflection](../../com.aspose.slides/reflection) مشخص شده برابر با [Reflection](../../com.aspose.slides/reflection) فعلی است. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

موقعیت شروع (در طول شیب‌دار گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

موقعیت شروع (در طول شیب‌دار گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

موقعیت انتها (در طول شیب‌دار گرادیان آلفا) مقدار آلفای انتها (درصد) را مشخص می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

موقعیت انتها (در طول شیب‌دار گرادیان آلفا) مقدار آلفای انتها (درصد) را مشخص می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

جهت جابجایی انعکاس. (زاویه). خواندنی/نوشتنی float.

**بازگشت:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

جهت جابجایی انعکاس. (زاویه). خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

شفافیت شروع انعکاس. (درصد). خواندنی/نوشتنی float.

**بازگشت:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

شفافیت شروع انعکاس. (درصد). خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

شفافیت انتهای انعکاس. (درصد). خواندنی/نوشتنی float.

**بازگشت:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

شفافیت انتهای انعکاس. (درصد). خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

شعاع تاری. خواندنی/نوشتنی double.

**بازگشت:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

شعاع تاری. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

جهت انعکاس. خواندنی/نوشتنی float.

**بازگشت:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

جهت انعکاس. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

فاصله انعکاس. خواندنی/نوشتنی double.

**بازگشت:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

فاصله انعکاس. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

ترازبندی مستطیل. خواندنی/نوشتنی [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**بازگشت:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

ترازبندی مستطیل. خواندنی/نوشتنی [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

زاویهٔ کج‌کردن افقی را مشخص می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

زاویهٔ کج‌کردن افقی را مشخص می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

زاویهٔ کج‌کردن عمودی را مشخص می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

زاویهٔ کج‌کردن عمودی را مشخص می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

مشخص می‌کند که آیا انعکاس باید همراه با شکل چرخانده شود اگر شکل چرخانده شود. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

مشخص می‌کند که آیا انعکاس باید همراه با شکل چرخانده شود اگر شکل چرخانده شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

عامل مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) خواندنی/نوشتنی double.

**بازگشت:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

عامل مقیاس افقی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

عامل مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) خواندنی/نوشتنی double.

**بازگشت:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

عامل مقیاس عمودی را مشخص می‌کند، مقیاس منفی باعث وارون شدن می‌شود. (درصد) خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

داده‌های مؤثر اثر انعکاس را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - یک [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

شی parent IPresentationComponent را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

مشخص می‌کند که آیا [Reflection](../../com.aspose.slides/reflection) مشخص شده برابر با [Reflection](../../com.aspose.slides/reflection) جاری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | [Reflection](../../com.aspose.slides/reflection) برای مقایسه. |

**بازگشت:**
boolean - true اگر اشیاء برابر باشند؛ در غیر این صورت false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند.

**بازگشت:**
int - یک کد هش برای شی جاری.