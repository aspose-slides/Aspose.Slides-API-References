---
title: PVIObject
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يحتوي على بنية أساسية للخدمات للكيانات التي يمكن أن تكون موضوعًا لوراثة قيم الخصائص.
type: docs
url: /ar/com.aspose.slides/pviobject/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

يحتوي على بنية أساسية للخدمات للكيانات التي يمكن أن تكون موضوعًا لوراثة قيم الخصائص.
## الطرق

| طريقة | وصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يقارن مع الكائن المحدد. |
| [hashCode()](#hashCode--) | يرجع رمز التجزئة. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

يرجع العنصر الأب IPresentationComponent. قراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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

يرجع الشريحة الأساسية. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

يرجع العرض التقديمي. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يقارن مع الكائن المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة. |

**الإرجاع:**
boolean - True إذا كانت الكائنات متساوية، وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يرجع رمز التجزئة.

**الإرجاع:**
int - رمز التجزئة.