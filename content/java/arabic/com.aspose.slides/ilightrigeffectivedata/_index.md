---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن ثابت يحتوي على خصائص سلسلة إضاءة فعّالة.
type: docs
url: /ar/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

كائن ثابت يحتوي على خصائص سلسلة إضاءة فعّالة.

--------------------

هذه الواجهة تُستخدم كجزء من [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| الطريقة | الوصف |
| --- | --- |
| [getDirection()](#getDirection--) | اتجاه الضوء. |
| [getLightType()](#getLightType--) | يمثل ضوءًا مسبقًا يمكن تطبيقه على الشكل. |
| [getRotation()](#getRotation--) | يتم تعريف الدوران باستخدام إحداثي خط العرض، وإحداثي خط الطول، وثورة حول المحور كإحداثيات لخط العرض وخط الطول. |

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

يمثل ضوءًا مسبقًا يمكن تطبيقه على الشكل. تمثل مجموعة الإضاءة مجموعة من الأضواء الموجهة بطريقة محددة بالنسبة إلى مشهد ثلاثي الأبعاد. للقراءة فقط [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**الإرجاع:**  
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف الدوران باستخدام إحداثي خط العرض، وإحداثي خط الطول، وثورة حول المحور كإحداثيات لخط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، الثاني - خط الطول، الثالث - الثورة.

**الإرجاع:**  
float[] - إحداثيات الدوران كقيمة float[]