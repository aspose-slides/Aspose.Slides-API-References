---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: يمثل LightRig.
type: docs
url: /ar/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

يمثل LightRig.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDirection()](#getDirection--) | اتجاه الضوء. |
| [setDirection(int value)](#setDirection-int-) | اتجاه الضوء. |
| [getLightType()](#getLightType--) | يمثل إضاءة مسبقة يمكن تطبيقها على شكل. |
| [setLightType(int value)](#setLightType-int-) | يمثل إضاءة مسبقة يمكن تطبيقها على شكل. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، وإحداثي خط الطول، ودورة حول المحور كإحداثي خط العرض وخط الطول. |
| [getRotation()](#getRotation--) | يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، وإحداثي خط الطول، ودورة حول المحور كإحداثي خط العرض وخط الطول. |
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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


يمثل إضاءة مسبقة يمكن تطبيقها على شكل. تمثل مجموعة الإضاءة مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة إلى مشهد ثلاثي الأبعاد. قراءة/كتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**القيمة المرجعة:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


يمثل إضاءة مسبقة يمكن تطبيقها على شكل. تمثل مجموعة الإضاءة مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة إلى مشهد ثلاثي الأبعاد. قراءة/كتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، وإحداثي خط الطول، ودورة حول المحور كإحداثي خط العرض وخط الطول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| latitude | float | إحداثي خط العرض من نوع float |
| longitude | float | إحداثي خط الطول من نوع float |
| revolution | float | إحداثي الدورة من نوع float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، وإحداثي خط الطول، ودورة حول المحور كإحداثي خط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، العنصر الثاني - خط الطول، العنصر الثالث - الدورة.

**القيمة المرجعة:**
float[] - إحداثيات الدوران كقائمة من float[]