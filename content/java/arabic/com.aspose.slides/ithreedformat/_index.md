---
title: IThreeDFormat
second_title: Aspose.Slides لمرجع واجهة برمجة تطبيقات جافا
description: يمثل خصائص ثلاثية الأبعاد.
type: docs
url: /ar/com.aspose.slides/ithreedformat/
---
**كل الواجهات التي تم تنفيذها:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

يمثل خصائص ثلاثية الأبعاد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | إرجاع أو تعيين عرض الشكل ثلاثي الأبعاد. |
| [setContourWidth(double value)](#setContourWidth-double-) | إرجاع أو تعيين عرض الشكل ثلاثي الأبعاد. |
| [getExtrusionHeight()](#getExtrusionHeight--) | إرجاع أو تعيين ارتفاع تأثير البثق. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | إرجاع أو تعيين ارتفاع تأثير البثق. |
| [getDepth()](#getDepth--) | إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. |
| [setDepth(double value)](#setDepth-double-) | إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. |
| [getBevelTop()](#getBevelTop--) | إرجاع أو تعيين نوع الحافة العلوية ثلاثية الأبعاد. |
| [getBevelBottom()](#getBevelBottom--) | إرجاع أو تعيين نوع الحافة السفلية ثلاثية الأبعاد. |
| [getContourColor()](#getContourColor--) | إرجاع أو تعيين لون الشكل الخارجي. |
| [getExtrusionColor()](#getExtrusionColor--) | إرجاع أو تعيين لون البثق. |
| [getCamera()](#getCamera--) | إرجاع أو تعيين إعدادات الكاميرا. |
| [getLightRig()](#getLightRig--) | إرجاع أو تعيين نوع الإضاءة. |
| [getMaterial()](#getMaterial--) | إرجاع أو تعيين نوع المادة. |
| [setMaterial(int value)](#setMaterial-int-) | إرجاع أو تعيين نوع المادة. |
| [getEffective()](#getEffective--) | الحصول على بيانات تنسيق ثلاثية الأبعاد الفعّالة مع تطبيق الوراثة. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


إرجاع أو تعيين عرض الشكل ثلاثي الأبعاد. قراءة/كتابة double.

**الإرجاع:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


إرجاع أو تعيين عرض الشكل ثلاثي الأبعاد. قراءة/كتابة double.

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


إرجاع أو تعيين ارتفاع تأثير البثق. قراءة/كتابة double.

**الإرجاع:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


إرجاع أو تعيين ارتفاع تأثير البثق. قراءة/كتابة double.

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. قراءة/كتابة double.

**الإرجاع:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. قراءة/كتابة double.

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


إرجاع أو تعيين نوع الحافة العلوية ثلاثية الأبعاد. قراءة فقط [IShapeBevel](../../com.aspose.slides/ishapebevel).

**الإرجاع:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


إرجاع أو تعيين نوع الحافة السفلية ثلاثية الأبعاد. قراءة فقط [IShapeBevel](../../com.aspose.slides/ishapebevel).

**الإرجاع:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


إرجاع أو تعيين لون الشكل الخارجي. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


إرجاع أو تعيين لون البثق. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


إرجاع أو تعيين إعدادات الكاميرا. قراءة فقط [ICamera](../../com.aspose.slides/icamera).

**الإرجاع:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


إرجاع أو تعيين نوع الإضاءة. قراءة فقط [ILightRig](../../com.aspose.slides/ilightrig).

**الإرجاع:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


إرجاع أو تعيين نوع المادة. قراءة/كتابة [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**الإرجاع:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


إرجاع أو تعيين نوع المادة. قراءة/كتابة [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


الحصول على بيانات تنسيق ثلاثية الأبعاد الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).