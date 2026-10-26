---
title: LightRig
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل LightRig.
type: docs
url: /ar/com.aspose.slides/lightrig/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)  
```
public final class LightRig extends PVIObject implements ILightRig
```

يمثل LightRig.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | اتجاه الضوء. |
| [setDirection(int value)](#setDirection-int-) | اتجاه الضوء. |
| [getLightType()](#getLightType--) | يمثل إضاءة مسبقة يمكن تطبيقها على شكل. |
| [setLightType(int value)](#setLightType-int-) | يمثل إضاءة مسبقة يمكن تطبيقها على شكل. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف دوران من خلال استخدام إحداثي خط عرض، وإحداثي خط طول، وثورة حول المحور كما إحداثيات خط العرض وخط الطول. |
| [getRotation()](#getRotation--) | يتم تعريف دوران من خلال استخدام إحداثي خط عرض، وإحداثي خط طول، وثورة حول المحور كما إحداثيات خط العرض وخط الطول. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. طويل للقراءة فقط.

**الإرجاع:**  
long

### getDirection() {#getDirection--}
```
public final int getDirection()
```

اتجاه الضوء. قابل للقراءة والكتابة [LightingDirection](../../com.aspose.slides/lightingdirection).

**الإرجاع:**  
int

### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

اتجاه الضوء. قابل للقراءة والكتابة [LightingDirection](../../com.aspose.slides/lightingdirection).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

يمثل إضاءة مسبقة يمكن تطبيقها على شكل. يمثل مجموعة من الأضواء موجهة بطريقة محددة بالنسبة لمشهد ثلاثي الأبعاد. قابل للقراءة والكتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**الإرجاع:**  
int

### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

يمثل إضاءة مسبقة يمكن تطبيقها على شكل. يمثل مجموعة من الأضواء موجهة بطريقة محددة بالنسبة لمشهد ثلاثي الأبعاد. قابل للقراءة والكتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

يتم تعريف دوران من خلال استخدام إحداثي خط عرض، وإحداثي خط طول، وثورة حول المحور كما إحداثيات خط العرض وخط الطول. إذا كان أي من قيم الإحداثيات هو Float.NaN، فإن كل دوران غير معرف.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

يتم تعريف دوران من خلال استخدام إحداثي خط عرض، وإحداثي خط طول، وثورة حول المح轴 كما إحداثيات خط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، الثاني - خط الطول، الثالث - الثورة. يرجع null إذا لم يُحدد دوران.

**الإرجاع:**  
float[]