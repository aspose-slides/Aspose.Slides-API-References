---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /ar/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

يمثل LightRig.
## الطرق

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | اتجاه الضوء. |
| [setDirection(int value)](#setDirection-int-) | اتجاه الضوء. |
| [getLightType()](#getLightType--) | يمثل إضاءة مسبقة يمين يمكن تطبيقها على شكل. |
| [setLightType(int value)](#setLightType-int-) | يمثل إضاءة مسبقة يمين يمكن تطبيقها على شكل. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف دوران باستخدام إحداثي عرض، إحداثي طول، وثورة حول المحور كإحداثي العرض والطول. |
| [getRotation()](#getRotation--) | يتم تعريف دوران باستخدام إحداثي عرض، إحداثي طول، وثورة حول المحور كإحداثي العرض والطول. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

اتجاه الضوء. قراءة/كتابة [LightingDirection](../../com.aspose.slides/lightingdirection).

**القيمة المرجعة:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

اتجاه الضوء. قراءة/كتابة [LightingDirection](../../com.aspose.slides/lightingdirection).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

يمثل إضاءة مسبقة يمين يمكن تطبيقها على شكل. تمثل مجموعة الإضاءة مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة لمشهد ثلاثي الأبعاد. قراءة/كتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**القيمة المرجعة:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

يمثل إضاءة مسبقة يمين يمكن تطبيقها على شكل. تمثل مجموعة الإضاءة مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة لمشهد ثلاثي الأبعاد. قراءة/كتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

يتم تعريف دوران باستخدام إحداثي عرض، إحداثي طول، وثورة حول المحور كإحداثي العرض والطول.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| latitude | float | إحداثي العرض float |
| longitude | float | إحداثي الطول float |
| revolution | float | إحداثي الثورة float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف دوران باستخدام إحداثي عرض، إحداثي طول، وثورة حول المحور كإحداثي العرض والطول. العنصر الأول في مصفوفة الإرجاع - العرض، الثاني - الطول، الثالث - الثورة.

**القيمة المرجعة:**
float[] - إحداثيات الدوران كقائمة float[]