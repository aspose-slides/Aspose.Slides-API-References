---
title: SectionCollection
second_title: Aspose.Slides لـ Android عبر مرجع API Java
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
| [get_Item(int index)](#get-Item-int-) | الحصول على العنصر في الفهرس المحدد. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | إضافة قسم شرائح يبدأ من الشريحة المحددة. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | إضافة قسم فارغ إلى نهاية المجموعة. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | إضافة قسم فارغ إلى الموضع المحدد في المجموعة. |
| [size()](#size--) | الحصول على عدد العناصر الموجودة فعليًا في المجموعة. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | إرجاع فهرس القسم المحدد في المجموعة. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | إزالة القسم والشرائح الموجودة داخل القسم. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | إزالة القسم. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | نقل القسم وشرائحه من المجموعة إلى الموضع المحدد. |
| [clear()](#clear--) | إزالة جميع الأقسام من المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ المجموعة بالكامل إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمتعدد الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
| [iterator()](#iterator--) | إرجاع عدّاد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرّر جافا للمجموعة بالكامل. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

الحصول على العنصر في الفهرس المحدد. قراءة فقط [ISection](../../com.aspose.slides/isection).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**  
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

إضافة قسم شرائح يبدأ من الشريحة المحددة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة الأولى للقسم |

**القيمة المرتجعة:**  
[ISection](../../com.aspose.slides/isection) - تمت إضافة القسم.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

إضافة قسم فارغ إلى نهاية المجموعة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |

**القيمة المرتجعة:**  
[ISection](../../com.aspose.slides/isection) - تمت إضافة القسم.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

إضافة قسم فارغ إلى الموضع المحدد في المجموعة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| index | int | فهرس القسم الجديد. |

**القيمة المرتجعة:**  
[ISection](../../com.aspose.slides/isection) - تمت إضافة القسم.
### size() {#size--}
```
public final int size()
```

الحصول على عدد العناصر الموجودة فعليًا في المجموعة. int قراءة فقط.

**القيمة المرتجعة:**  
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

إرجاع فهرس القسم المحدد في المجموعة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المطلوب العثور عليه. |

**القيمة المرتجعة:**  
int - فهرس القسم أو -1 إذا لم يكن القسم جزءًا من هذه المجموعة.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

إزالة القسم والشرائح الموجودة داخل القسم.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد إزالته من المجموعة. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

إزالة القسم. سيتم دمج الشرائح الموجودة في القسم مع القسم السابق.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد إزالته من المجموعة. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

نقل القسم وشرائحه من المجموعة إلى الموضع المحدد.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد نقله. |
| index | int | الفهرس المستهدف. |
### clear() {#clear--}
```
public final void clear()
```

إزالة جميع الأقسام من المجموعة.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ المجموعة بالكامل إلى المصفوفة المحددة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة |
| index | int | الفهرس في المصفوفة المستهدفة. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمتعدد الخيوط). boolean قراءة فقط.

**القيمة المرتجعة:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر التزامن. Object قراءة فقط.

**القيمة المرتجعة:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

إرجاع عدّاد يتنقل عبر المجموعة.

**القيمة المرتجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - عدّاد يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

إرجاع مكرّر جافا للمجموعة بالكامل.

**القيمة المرتجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - java.util.Iterator للمجموعة بالكامل.