---
title: IThreeDFormatEffectiveData
second_title: مرجع API لـ Aspose.Slides للغة Java
description: كائن غير قابل للتغيير يمثل خصائص تنسيق ثلاثية الأبعاد الفعّالة.
type: docs
url: /ar/com.aspose.slides/ithreedformateffectivedata/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

كائن غير قابل للتغيير يمثل خصائص التنسيق ثلاثي الأبعاد الفعّالة.

--------------------

تُستخدم هذه الواجهة مع واجهة [IThreeDFormat](../../com.aspose.slides/ithreedformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | يرجع عرض الشكل ثلاثي الأبعاد. |
| [getExtrusionHeight()](#getExtrusionHeight--) | يرجع ارتفاع تأثير البثق. |
| [getDepth()](#getDepth--) | يرجع عمق الشكل ثلاثي الأبعاد. |
| [getBevelTop()](#getBevelTop--) | يرجع نوع الحافة العلوية ثلاثية الأبعاد. |
| [getBevelBottom()](#getBevelBottom--) | يرجع نوع الحافة السفلية ثلاثية الأبعاد. |
| [getContourColor()](#getContourColor--) | يرجع لون الحافة. |
| [getExtrusionColor()](#getExtrusionColor--) | يرجع لون البثق. |
| [getCamera()](#getCamera--) | يرجع إعدادات الكاميرا. |
| [getLightRig()](#getLightRig--) | يرجع نوع الإضاءة. |
| [getMaterial()](#getMaterial--) | يرجع نوع المادة. |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

يرجع عرض الشكل ثلاثي الأبعاد. قراءة فقط double.

**القيمة المرجعة:**
double

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

يرجع ارتفاع تأثير البثق. قراءة فقط double.

**القيمة المرجعة:**
double

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

يرجع عمق الشكل ثلاثي الأبعاد. قراءة فقط double.

**القيمة المرجعة:**
double

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

يرجع نوع الحافة العلوية ثلاثية الأبعاد. قراءة فقط [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**القيمة المرجعة:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

يرجع نوع الحافة السفلية ثلاثية الأبعاد. قراءة فقط [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**القيمة المرجعة:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

يرجع لون الحافة. قراءة فقط java.awt.Color.

**القيمة المرجعة:**
java.awt.Color

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

يرجع لون البثق. قراءة فقط java.awt.Color.

**القيمة المرجعة:**
java.awt.Color

### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

يرجع إعدادات الكاميرا. قراءة فقط [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**القيمة المرجعة:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)

### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

يرجع نوع الإضاءة. قراءة فقط [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**القيمة المرجعة:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

يرجع نوع المادة. قراءة فقط [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**القيمة المرجعة:**
int