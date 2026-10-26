---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides للـ Android عبر مرجع API لجافا
description: كائن غير قابل للتغيير يمثل خصائص تنسيق ثلاثي الأبعاد الفعّالة.
type: docs
url: /ar/com.aspose.slides/ithreedformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

كائن غير قابل للتغيير يمثل الخصائص الفعالة لتنسيق ثلاثي الأبعاد.

--------------------

يتم استخدام هذه الواجهة مع واجهة [IThreeDFormat](../../com.aspose.slides/ithreedformat) لإرجاع قيم التنسيق الفعالة مع تطبيق الوراثة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Returns the width of a 3D contour. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returns the height of an extrusion effect. |
| [getDepth()](#getDepth--) | Returns the depth of a 3D shape. |
| [getBevelTop()](#getBevelTop--) | Returns the type of a top 3D bevel. |
| [getBevelBottom()](#getBevelBottom--) | Returns the type of a bottom 3D bevel. |
| [getContourColor()](#getContourColor--) | Returns the color of a contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Returns the color of an extrusion. |
| [getCamera()](#getCamera--) | Returns the settings of a camera. |
| [getLightRig()](#getLightRig--) | Returns the type of a light. |
| [getMaterial()](#getMaterial--) | Returns the type of a material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


يرجع عرض حدود ثلاثية الأبعاد. للقراءة فقط double.

**الإرجاع:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


يرجع ارتفاع تأثير البثق. للقراءة فقط double.

**الإرجاع:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


يرجع عمق الشكل ثلاثي الأبعاد. للقراءة فقط double.

**الإرجاع:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


يرجع نوع الحافة العلوية ثلاثية الأبعاد. للقراءة فقط [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**الإرجاع:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


يرجع نوع الحافة السفلية ثلاثية الأبعاد. للقراءة فقط [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**الإرجاع:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


يرجع لون الحد. للقراءة فقط java.lang.Integer.

**الإرجاع:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


يرجع لون البثق. للقراءة فقط java.lang.Integer.

**الإرجاع:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


يرجع إعدادات الكاميرا. للقراءة فقط [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**الإرجاع:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


يرجع نوع الإضاءة. للقراءة فقط [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**الإرجاع:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


يرجع نوع المادة. للقراءة فقط [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**الإرجاع:**
int