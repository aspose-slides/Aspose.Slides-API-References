---
title: IThreeDFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يُمثّل خصائص ثلاثية الأبعاد.
type: docs
url: /ar/com.aspose.slides/ithreedformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

يمثّل خصائص ثلاثية الأبعاد.
## الدوال

| الطريقة | الوصف |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | إرجاع أو تعيين عرض حد ثلاثي الأبعاد. |
| [setContourWidth(double value)](#setContourWidth-double-) | إرجاع أو تعيين عرض حد ثلاثي الأبعاد. |
| [getExtrusionHeight()](#getExtrusionHeight--) | إرجاع أو تعيين ارتفاع تأثير البثق. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | إرجاع أو تعيين ارتفاع تأثير البثق. |
| [getDepth()](#getDepth--) | إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. |
| [setDepth(double value)](#setDepth-double-) | إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. |
| [getBevelTop()](#getBevelTop--) | إرجاع أو تعيين نوع حد ثلاثي الأبعاد أعلى. |
| [getBevelBottom()](#getBevelBottom--) | إرجاع أو تعيين نوع حد ثلاثي الأبعاد سفلي. |
| [getContourColor()](#getContourColor--) | إرجاع أو تعيين لون الحد. |
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


إرجاع أو تعيين عرض حد ثلاثي الأبعاد. قراءة/كتابة double.

**القيمة المرجعة:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


إرجاع أو تعيين عرض حد ثلاثي الأبعاد. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


إرجاع أو تعيين ارتفاع تأثير البثق. قراءة/كتابة double.

**القيمة المرجعة:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


إرجاع أو تعيين ارتفاع تأثير البثق. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. قراءة/كتابة double.

**القيمة المرجعة:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


إرجاع أو تعيين عمق الشكل ثلاثي الأبعاد. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


إرجاع أو تعيين نوع حد ثلاثي الأبعاد أعلى. قراءة فقط [IShapeBevel](../../com.aspose.slides/ishapebevel).

**القيمة المرجعة:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


إرجاع أو تعيين نوع حد ثلاثي الأبعاد سفلي. قراءة فقط [IShapeBevel](../../com.aspose.slides/ishapebevel).

**القيمة المرجعة:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


إرجاع أو تعيين لون الحد. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


إرجاع أو تعيين لون البثق. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


إرجاع أو تعيين إعدادات الكاميرا. قراءة فقط [ICamera](../../com.aspose.slides/icamera).

**القيمة المرجعة:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


إرجاع أو تعيين نوع الإضاءة. قراءة فقط [ILightRig](../../com.aspose.slides/ilightrig).

**القيمة المرجعة:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


إرجاع أو تعيين نوع المادة. قراءة/كتابة [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**القيمة المرجعة:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


إرجاع أو تعيين نوع المادة. قراءة/كتابة [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


الحصول على بيانات تنسيق ثلاثية الأبعاد الفعّالة مع تطبيق الوراثة.

**القيمة المرجعة:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).