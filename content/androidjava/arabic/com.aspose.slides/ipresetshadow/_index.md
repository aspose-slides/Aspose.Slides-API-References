---
title: IPresetShadow
second_title: Aspose.Slides للـ Android عبر مرجع API لجافا
description: يمثل تأثير ظل محدد مسبقًا.
type: docs
url: /ar/com.aspose.slides/ippresetshadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

يمثل تأثير ظل محدد مسبقًا.
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

**القيمة المرجعة:**
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

**القيمة المرجعة:**
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

لون الظل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

الإعداد المسبق. قراءة/كتابة [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**القيمة المرجعة:**
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