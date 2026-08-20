---
title: SmartArtShapeCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من أشكال SmartArt
type: docs
url: /ar/com.aspose.slides/smartartshapecollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

يمثل مجموعة من أشكال SmartArt
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن عبر الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مُكرِّر java للمجموعة بأكملها. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قابل للقراءة فقط int.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد. قابل للقراءة فقط [SmartArtShape](../../com.aspose.slides/smartartshape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشكل |

**الإرجاع:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - شكل SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن عبر الخيوط). قابل للقراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. قابل للقراءة فقط Object.

**الإرجاع:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة. |
| index | int | فهرس البداية في المصفوفة المستهدفة. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

يعيد عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

يعيد مُكرِّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - java.util.Iterator للمجموعة بأكملها.