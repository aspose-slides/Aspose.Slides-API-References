---
title: SoftEdge
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل تأثير الحافة الناعمة.
type: docs
url: /ar/com.aspose.slides/softedge/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

يمثل تأثير الحافة الناعمة. حواف الشكل مشوشة، بينما التعبئة غير متأثرة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | يحدد نصف قطر التشويش لتطبيقه على الحواف. |
| [setRadius(double value)](#setRadius-double-) | يحدد نصف قطر التشويش لتطبيقه على الحواف. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير الحافة الناعمة الفعّالة مع تطبيق الوراثة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [SoftEdge](../../com.aspose.slides/softedge) المحدد مساوٍ للـ [SoftEdge](../../com.aspose.slides/softedge) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

يحدد نصف قطر التشويش لتطبيقه على الحواف. قراءة/كتابة double.

**الإرجاع:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

يحدد نصف قطر التشويش لتطبيقه على الحواف. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

يحصل على بيانات تأثير الحافة الناعمة الفعّالة مع تطبيق الوراثة.

**الإرجاع:**  
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

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

إرجاع IPresentationComponent الأب. قراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [SoftEdge](../../com.aspose.slides/softedge) المحدد مساوٍ للـ [SoftEdge](../../com.aspose.slides/softedge) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال[SoftEdge](../../com.aspose.slides/softedge) للمقارنة. |

**الإرجاع:**  
boolean - صحيح إذا كانت الكائنات متساوية؛ وإلا، خطأ.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**  
int - رمز تجزئة للكائن الحالي.