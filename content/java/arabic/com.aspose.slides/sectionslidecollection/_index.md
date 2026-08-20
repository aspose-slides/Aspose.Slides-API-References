---
title: SectionSlideCollection
second_title: مرجع API Aspose.Slides for Java
description: يمثل مجموعة من الشرائح في القسم.
type: docs
url: /ar/com.aspose.slides/sectionslidecollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)  
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

يمثل مجموعة من الشرائح في القسم.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [size()](#size--) | يحصل على عدد العناصر الفعلي الموجودة في المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ المجموعة بالكامل إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمتعدد الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مُكرِّر java للمجموعة بأكملها. |

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISlide](../../com.aspose.slides/islide)

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلي الموجودة في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ المجموعة بالكامل إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف |
| index | int | الفهرس في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمتعدد الخيوط). للقراءة فقط boolean.

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
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - يمكن استخدام IGenericEnumerator للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

يرجع مُكرِّر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator للمجموعة بأكملها.