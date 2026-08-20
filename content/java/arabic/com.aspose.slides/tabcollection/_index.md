---
title: TabCollection
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل مجموعة من علامات التبويب.
type: docs
url: /ar/com.aspose.slides/tabcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

يمثل مجموعة من علامات التبويب.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يتم الحصول على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يتم الحصول على العنصر في الفهرس المحدد. |
| [add(double position, int align)](#add-double-int-) | يضيف Tab إلى المجموعة. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | يضيف Tab إلى المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت مثيلات TabsEx اثنتين متساويتين. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرِّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامَنًا (آمن للthread). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |
### size() {#size--}
```
public final int size()
```

يتم الحصول على عدد العناصر الموجودة فعليًا في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

يتم الحصول على العنصر في الفهرس المحدد. [Tab](../../com.aspose.slides/tab) للقراءة فقط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

يضيف Tab إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**الإرجاع:**
[ITab](../../com.aspose.slides/itab) - تم إضافة علامة التبويب.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

يضيف Tab إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | كائن Tab المراد إضافته في نهاية المجموعة. |

**الإرجاع:**
int - الفهرس الذي تمت فيه إضافة علامة التبويب.
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**الإرجاع:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كانت مثيلات TabsEx اثنتين متساويتين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx للمقارنة مع TabsEx الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الـ TabsEx المحدد مساويًا للـ TabsEx الحالي؛ وإلا **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

يرجع مكرِّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة. |
| index | int | الفهرس الابتدائي في المصفوفة المستهدفة. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامَنًا (آمن للthread). boolean للقراءة فقط.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. Object للقراءة فقط.

**الإرجاع:**
java.lang.Object