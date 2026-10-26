---
title: LightRig
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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
| [getLightType()](#getLightType--) | يمثل إعداد إضاءة مسبق يمكن تطبيقه على شكل. |
| [setLightType(int value)](#setLightType-int-) | يمثل إعداد إضاءة مسبق يمكن تطبيقه على شكل. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثي latitude و longitude. |
| [getRotation()](#getRotation--) | يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثي latitude و longitude. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قيمة من نوع long للقراءة فقط.

**القيمة المرجعة:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

اتجاه الضوء. قراءة/كتابة [LightingDirection](../../com.aspose.slides/lightingdirection).

**القيمة المرجعة:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

اتجاه الضوء. قراءة/كتابة [LightingDirection](../../com.aspose.slides/lightingdirection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

يمثل إعداد إضاءة مسبق يمكن تطبيقه على شكل. يمثل light rig مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة إلى مشهد ثلاثي الأبعاد. قراءة/كتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**القيمة المرجعة:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

يمثل إعداد إضاءة مسبق يمكن تطبيقه على شكل. يمثل light rig مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة إلى مشهد ثلاثي الأبعاد. قراءة/كتابة [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثي latitude و longitude. إذا كان أي من قيم الإحداثيات هو Float.NaN، فإن كل دوران غير معرّف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثي latitude و longitude. العنصر الأول في مصفوفة الإرجاع - latitude، الثاني - longitude، الثالث - revolution. تُرجع null إذا لم يُعرّف أي دوران.

**القيمة المرجعة:**
float[]