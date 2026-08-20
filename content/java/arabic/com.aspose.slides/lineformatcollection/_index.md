---
title: LineFormatCollection
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل مجموعة أنماط الخط.
type: docs
url: /ar/com.aspose.slides/lineformatcollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

يمثل مجموعة أنماط الخط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [iterator()](#iterator--) | يرّجّع عدًّا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرّجّع java iterator للمجموعة بأكملها. |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرّجّع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمواضيع). |
| [getSyncRoot()](#getSyncRoot--) | يرّجّع جذر المزامنة. |
### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

يرجع عدًّا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

يرجع java iterator للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - java.util.Iterator للمجموعة بأكملها.
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة. |
| index | int | الفهرس الابتدائي في المصفوفة المستهدفة. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمواضيع). للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. للقراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object