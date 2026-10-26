---
title: Glow
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل تأثير Glow حيث يتم إضافة مخطط ملون مشوش خارج حواف الكائن.
type: docs
url: /ar/com.aspose.slides/glow/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

يمثل تأثير Glow، حيث يتم إضافة مخطط ملون مشوش خارج حواف الكائن.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | نصف القطر. |
| [setRadius(double value)](#setRadius-double-) | نصف القطر. |
| [getColor()](#getColor--) | تنسيق اللون. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Glow الفعالة مع تطبيق الوراثة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [Glow](../../com.aspose.slides/glow) المحدد يساوي [Glow](../../com.aspose.slides/glow) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

نصف القطر. قابل للقراءة والكتابة  double .

**القيمة المرجعة:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

نصف القطر. قابل للقراءة والكتابة  double .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

تنسيق اللون. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

يحصل على بيانات تأثير Glow الفعالة مع تطبيق الوراثة.

**القيمة المرجعة:**  
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

الإصدار. للقراءة فقط long.

**القيمة المرجعة:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

يرجع parent IPresentationComponent. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**القيمة المرجعة:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [Glow](../../com.aspose.slides/glow) المحدد يساوي [Glow](../../com.aspose.slides/glow) الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ [Glow](../../com.aspose.slides/glow) للمقارنة. |

**القيمة المرجعة:**  
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**القيمة المرجعة:**  
int - رمز تجزئة للكائن الحالي.