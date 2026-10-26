---
title: SoftEdge
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل تأثير حافة ناعمة.
type: docs
url: /ar/com.aspose.slides/softedge/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

يمثل تأثير الحافة الناعمة. حواف الشكل مضببة، بينما التعبئة لا تتأثر.
## الطرق

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | يحدد نصف قطر الضبابية لتطبيقه على الحواف. |
| [setRadius(double value)](#setRadius-double-) | يحدد نصف قطر الضبابية لتطبيقه على الحواف. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير الحافة الناعمة الفعلية مع تطبيق الوراثة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [SoftEdge](../../com.aspose.slides/softedge) المحدد مساويًا لـ [SoftEdge](../../com.aspose.slides/softedge) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

يحدد نصف قطر الضبابية لتطبيقه على الحواف. قابل للقراءة/الكتابة double.

**الإرجاع:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

يحدد نصف قطر الضبابية لتطبيقه على الحواف. قابل للقراءة/الكتابة double.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

يحصل على بيانات تأثير الحافة الناعمة الفعلية مع تطبيق الوراثة.

**الإرجاع:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قابل للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. قابل للقراءة فقط long.

**الإرجاع:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع العنصر الأب IPresentationComponent. قابل للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [SoftEdge](../../com.aspose.slides/softedge) المحدد مساويًا لـ [SoftEdge](../../com.aspose.slides/softedge) الحالي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | الـ [SoftEdge](../../com.aspose.slides/softedge) للمقارنة. |

**الإرجاع:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.