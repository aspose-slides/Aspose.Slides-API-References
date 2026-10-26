---
title: IPresetShadow
second_title: مرجع API Aspose.Slides للجاڤا
description: يمثّل تأثير الظل المُسبق.
type: docs
url: /ar/com.aspose.slides/ipresetshadow/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

يمثل تأثير الظل المُسبق.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDirection()](#getDirection--) | اتجاه الظل. |
| [setDirection(float value)](#setDirection-float-) | اتجاه الظل. |
| [getDistance()](#getDistance--) | مسافة الظل. |
| [setDistance(double value)](#setDistance-double-) | مسافة الظل. |
| [getShadowColor()](#getShadowColor--) | لون الظل. |
| [getPreset()](#getPreset--) | الإعداد المسبق. |
| [setPreset(int value)](#setPreset-int-) | الإعداد المسبق. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

اتجاه الظل. قراءة/كتابة float.

**القيمة المرتجعة:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

اتجاه الظل. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

مسافة الظل. قراءة/كتابة double.

**القيمة المرتجعة:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

مسافة الظل. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

لون الظل. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرتجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

الإعداد المسبق. قراءة/كتابة [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**القيمة المرتجعة:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

الإعداد المسبق. قراءة/كتابة [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |