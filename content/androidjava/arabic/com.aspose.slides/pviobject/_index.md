---
title: PVIObject
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يحتوي على بنية أساسية للخدمة للكائنات التي يمكن أن تكون موضوعًا لتوريث قيم الخصائص.
type: docs
url: /ar/com.aspose.slides/pviobject/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

يحتوي على بنية أساسية لخدمة الكائنات التي يمكن أن تكون موضوعًا لتوريث قيم الخصائص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares with specified object. |
| [hashCode()](#hashCode--) | Returns hash code. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

إرجاع الوالد IPresentationComponent. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**الإرجاع:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

إرجاع الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

إرجاع العرض التقديمي. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يقارن مع الكائن المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة. |

**الإرجاع:**
boolean - true إذا كان الكائنان متساويين، وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

إرجاع رمز التجزئة.

**الإرجاع:**
int - رمز التجزئة.