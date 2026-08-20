---
title: SectionCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من الأقسام.
type: docs
url: /ar/com.aspose.slides/sectioncollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

يمثل مجموعة من الأقسام.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | إضافة قسم شرائح يبدأ من شريحة محددة. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | إضافة قسم فارغ إلى نهاية المجموعة. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | إضافة قسم فارغ إلى الموضع المحدد في المجموعة. |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعلياً في المجموعة. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | يرجع فهرس القسم المحدد في المجموعة. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | إزالة القسم والشرائح الموجودة في القسم. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | إزالة القسم. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | نقل القسم وشرائحه من المجموعة إلى الموضع المحدد. |
| [clear()](#clear--) | إزالة جميع الأقسام من المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ المجموعة كاملة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |
| [iterator()](#iterator--) | يرجع عداداً يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّر Java للمجموعة كاملة. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ISection](../../com.aspose.slides/isection).

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

إضافة قسم شرائح يبدأ من شريحة محددة.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة الأولى للقسم |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection) - تم إضافة القسم.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

إضافة قسم فارغ إلى نهاية المجموعة.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection) - تم إضافة القسم.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

إضافة قسم فارغ إلى الموضع المحدد في المجموعة.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| index | int | فهرس القسم الجديد. |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection) - تم إضافة القسم.
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعلياً في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

يرجع فهرس القسم المحدد في المجموعة.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للبحث عنه. |

**القيمة المرجعة:**
int - فهرس القسم أو -1 إذا لم يكن القسم من هذه المجموعة.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

إزالة القسم والشرائح الموجودة في القسم.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم لإزالته من المجموعة. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

إزالة القسم. الشرائح الموجودة في القسم ستدمج في القسم السابق.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم لإزالته من المجموعة. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

نقل القسم وشرائحه من المجموعة إلى الموضع المحدد.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للنقل. |
| index | int | الفهرس الهدف. |
### clear() {#clear--}
```
public final void clear()
```

إزالة جميع الأقسام من المجموعة.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ المجموعة كاملة إلى المصفوفة المحددة.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف |
| index | int | الفهرس في المصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. للقراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

يرجع عداداً يتجول عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - يمكن استخدام IGenericEnumerator للتجول عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

يرجع مكرّر Java للمجموعة كاملة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - java.util.Iterator للمجموعة كاملة.