---
title: PresetShadow
second_title: مرجع API ل Aspose.Slides للـ Java
description: يمثل تأثير ظل مُعد مسبقًا.
type: docs
url: /ar/com.aspose.slides/presetshadow/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

يمثل تأثير ظل مُعد مسبقًا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDirection()](#getDirection--) | اتجاه الظل. |
| [setDirection(float value)](#setDirection-float-) | اتجاه الظل. |
| [getDistance()](#getDistance--) | مسافة الظل. |
| [setDistance(double value)](#setDistance-double-) | مسافة الظل. |
| [getShadowColor()](#getShadowColor--) | لون الظل. |
| [getPreset()](#getPreset--) | إعداد مسبق. |
| [setPreset(int value)](#setPreset-int-) | إعداد مسبق. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير الظل المعد مسبقًا الفعّالة مع تطبيق الوراثة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [PresetShadow](../../com.aspose.slides/presetshadow) المحدد يساوي [PresetShadow](../../com.aspose.slides/presetshadow) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

اتجاه الظل. قابل للقراءة والكتابة  float .

**الإرجاع:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

اتجاه الظل. قابل للقراءة والكتابة  float .

**معاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

مسافة الظل. قابل للقراءة والكتابة  double .

**الإرجاع:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

مسافة الظل. قابل للقراءة والكتابة  double .

**معاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

لون الظل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

إعداد مسبق. قابل للقراءة والكتابة [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**الإرجاع:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

إعداد مسبق. قابل للقراءة والكتابة [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**معاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

يحصل على بيانات تأثير الظل المعد مسبقًا الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع العنصر الأب IPresentationComponent. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [PresetShadow](../../com.aspose.slides/presetshadow) المحدد يساوي [PresetShadow](../../com.aspose.slides/presetshadow) الحالي.

**معاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) للمقارنة. |

**الإرجاع:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.