---
title: ILightRigEffectiveData
second_title: Aspose.Slides للـ Android عبر مرجع Java API
description: كائن غير قابل للتغيير يحتوي على خصائص rig الإضاءة الفعّالة.
type: docs
url: /ar/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص rig الإضاءة الفعّالة.

--------------------

هذه الواجهة تُستخدم كجزء من [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| الطريقة | الوصف |
| --- | --- |
| [getDirection()](#getDirection--) | اتجاه الضوء. |
| [getLightType()](#getLightType--) | يمثل ضوءًا مسبقًا يمكن تطبيقه على شكل. |
| [getRotation()](#getRotation--) | يتم تعريف الدوران باستخدام إحداثي خط العرض، إحداثي خط الطول، ودورة حول المحور كإحداثيات خط العرض وخط الطول. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

اتجاه الضوء. للقراءة فقط [LightingDirection](../../com.aspose.slides/lightingdirection).

**الإرجاع:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

يمثل ضوءًا مسبقًا يمكن تطبيقه على شكل. يمثل rig الإضاءة مجموعة من الأضواء المرتبة بطريقة محددة بالنسبة إلى مشهد ثلاثي الأبعاد. للقراءة فقط [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**الإرجاع:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف الدوران باستخدام إحداثي خط العرض، إحداثي خط الطول، ودورة حول المحور كإحداثيات خط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، الثاني - خط الطول، الثالث - الدورة.

**الإرجاع:**
float[] - إحداثيات الدوران كـ float[]