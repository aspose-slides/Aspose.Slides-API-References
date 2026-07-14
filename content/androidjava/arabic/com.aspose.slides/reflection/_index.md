---
title: Reflection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يمثل تأثير انعكاس.
type: docs
url: /ar/com.aspose.slides/reflection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

يمثل تأثير انعكاس.  
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | يحدد موضع البدء (على منحدر تدرج ألفا) لقيمة ألفا البدء (نسبة مئوية). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | يحدد موضع البدء (على منحدر تدرج ألفا) لقيمة ألفا البدء (نسبة مئوية). |
| [getEndPosAlpha()](#getEndPosAlpha--) | يحدد موضع النهاية (على منحدر تدرج ألفا) لقيمة ألفا النهاية (نسبة مئوية). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | يحدد موضع النهاية (على منحدر تدرج ألفا) لقيمة ألفا النهاية (نسبة مئوية). |
| [getFadeDirection()](#getFadeDirection--) | يحدد اتجاه إزاحة الانعكاس. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | يحدد اتجاه إزاحة الانعكاس. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | شفافية الانعكاس الابتدائية. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | شفافية الانعكاس الابتدائية. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | شفافية الانعكاس النهائية. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | شفافية الانعكاس النهائية. |
| [getBlurRadius()](#getBlurRadius--) | نصف قطر الضبابية. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | نصف قطر الضبابية. |
| [getDirection()](#getDirection--) | اتجاه الانعكاس. |
| [setDirection(float value)](#setDirection-float-) | اتجاه الانعكاس. |
| [getDistance()](#getDistance--) | مسافة الانعكاس. |
| [setDistance(double value)](#setDistance-double-) | مسافة الانعكاس. |
| [getRectangleAlign()](#getRectangleAlign--) | محاذاة المستطيل. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | محاذاة المستطيل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | يحدد زاوية الانحراف الأفقي. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | يحدد زاوية الانحراف الأفقي. |
| [getSkewVertical()](#getSkewVertical--) | يحدد زاوية الانحراف العمودي. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | يحدد زاوية الانحراف العمودي. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. |
| [getScaleHorizontal()](#getScaleHorizontal--) | يحدد معامل التحجيم الأفقي، التحجيم السالب يسبب انعكاسًا. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | يحدد معامل التحجيم الأفقي، التحجيم السالب يسبب انعكاسًا. |
| [getScaleVertical()](#getScaleVertical--) | يحدد معامل التحجيم العمودي، التحجيم السالب يسبب انعكاسًا. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | يحدد معامل التحجيم العمودي، التحجيم السالب يسبب انعكاسًا. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير الانعكاس الفعّالة مع تطبيق الوراثة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [Reflection](../../com.aspose.slides/reflection) المحدد مساويًا للـ [Reflection](../../com.aspose.slides/reflection) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

يحدد موضع البدء (على منحدر تدرج ألفا) لقيمة ألفا البدء (نسبة مئوية). قراءة/كتابة float.

**الإرجاع:**  
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

يحدد موضع البدء (على منحدر تدرج ألفا) لقيمة ألفا البدء (نسبة مئوية). قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

يحدد موضع النهاية (على منحدر تدرج ألفا) لقيمة ألفا النهاية (نسبة مئوية). قراءة/كتابة float.

**الإرجاع:**  
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

يحدد موضع النهاية (على منحدر تدرج ألفا) لقيمة ألفا النهاية (نسبة مئوية). قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

يحدد اتجاه إزاحة الانعكاس (زاوية). قراءة/كتابة float.

**الإرجاع:**  
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

يحدد اتجاه إزاحة الانعكاس (زاوية). قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

شفافية الانعكاس الابتدائية (نسبة مئوية). قراءة/كتابة float.

**الإرجاع:**  
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

شفافية الانعكاس الابتدائية (نسبة مئوية). قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

شفافية الانعكاس النهائية (نسبة مئوية). قراءة/كتابة float.

**الإرجاع:**  
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

شفافية الانعكاس النهائية (نسبة مئوية). قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

نصف قطر الضبابية. قراءة/كتابة double.

**الإرجاع:**  
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

نصف قطر الضبابية. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

اتجاه الانعكاس. قراءة/كتابة float.

**الإرجاع:**  
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

اتجاه الانعكاس. قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

مسافة الانعكاس. قراءة/كتابة double.

**الإرجاع:**  
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

مسافة الانعكاس. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

محاذاة المستطيل. قراءة/كتابة [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**الإرجاع:**  
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

محاذاة المستطيل. قراءة/كتابة [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

يحدد زاوية الانحراف الأفقي. قراءة/كتابة double.

**الإرجاع:**  
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

يحدد زاوية الانحراف الأفقي. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

يحدد زاوية الانحراف العمودي. قراءة/كتابة double.

**الإرجاع:**  
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

يحدد زاوية الانحراف العمودي. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. قراءة/كتابة boolean.

**الإرجاع:**  
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

يحدد ما إذا كان يجب أن يدور الانعكاس مع الشكل إذا تم تدوير الشكل. قراءة/كتابة boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

يحدد معامل التحجيم الأفقي، التحجيم السالب يسبب انعكاسًا (نسبة مئوية). قراءة/كتابة double.

**الإرجاع:**  
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

يحدد معامل التحجيم الأفقي، التحجيم السالب يسبب انعكاسًا (نسبة مئوية). قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

يحدد معامل التحجيم العمودي، التحجيم السالب يسبب انعكاسًا (نسبة مئوية). قراءة/كتابة double.

**الإرجاع:**  
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

يحدد معامل التحجيم العمودي، التحجيم السالب يسبب انعكاسًا (نسبة مئوية). قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

يحصل على بيانات تأثير الانعكاس الفعّالة مع تطبيق الوراثة.

**الإرجاع:**  
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع العنصر الأب IPresentationComponent. قراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [Reflection](../../com.aspose.slides/reflection) المحدد مساويًا للـ [Reflection](../../com.aspose.slides/reflection) الحالي.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ [Reflection](../../com.aspose.slides/reflection) للمقارنة. |

**الإرجاع:**  
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**  
int - A hash code for the current object.