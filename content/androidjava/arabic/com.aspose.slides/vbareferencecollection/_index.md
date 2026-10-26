---
title: VbaReferenceCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يمثل مجموعة من مراجع مشروع VBA.
type: docs
url: /ar/com.aspose.slides/vbareferencecollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

يمثل مجموعة من مراجع مشروع VBA.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يُعيد عدد العناصر الفعلية الموجودة في المجموعة. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | يضيف المرجع الجديد إلى مجموعة المراجع |
| [get_Item(int index)](#get-Item-int-) | يسترجع العنصر في الفهرس المحدد. |
| [iterator()](#iterator--) | يُعيد مُعدد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُعيد مكرر Java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينَسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يُعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يُعيد جذر المزامنة. |
### size() {#size--}
```
public final int size()
```


يُعيد عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```


يضيف المرجع الجديد إلى مجموعة المراجع

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```


يسترجع العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```


يُعيد مُعدد يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```


يُعيد مكرر Java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس البداية في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


يُعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


يُعيد جذر المزامنة. للقراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object