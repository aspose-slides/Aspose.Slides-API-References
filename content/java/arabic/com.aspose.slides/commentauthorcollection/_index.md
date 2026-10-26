---
title: CommentAuthorCollection
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل مجموعة من مؤلفي التعليقات.
type: docs
url: /ar/com.aspose.slides/commentauthorcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)  
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

يمثل مجموعة من مؤلفي التعليقات.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | يضيف مؤلفًا جديدًا في نهاية المجموعة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين. |
| [findByName(String name)](#findByName-java.lang.String-) | يبحث عن مؤلف في المجموعة بالاسم. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | يبحث عن مؤلف في المجموعة بالاسم والحرفين الأوليين. |
| [removeAt(int index)](#removeAt-int-) | يزيل المؤلف في الفهرس المحدد من المجموعة. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | يزيل أول ظهور للمؤلف المحدد في المجموعة. |
| [clear()](#clear--) | يزيل جميع المؤلفين من المجموعة. |
| [iterator()](#iterator--) | يعيد كائن تعداد يمكنه iterates خلال المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد java iterator للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط int.

**Returns:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

يضيف مؤلفًا جديدًا في نهاية المجموعة.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف الجديد. |
| initials | java.lang.String | الحروف الأولى للمؤلف الجديد. |

**Returns:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - كائن [ICommentAuthor](../../com.aspose.slides/icommentauthor) جديد.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين.

**Returns:**  
com.aspose.slides.ICommentAuthor[] - مصفوفة من [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

يبحث عن مؤلف في المجموعة بالاسم.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف المراد البحث عنه. |

**Returns:**  
com.aspose.slides.ICommentAuthor[] - المؤلف أو null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

يبحث عن مؤلف في المجموعة بالاسم والحرفين الأوليين.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف المراد البحث عنه. |
| initials | java.lang.String | الحروف الأولى للمؤلف المراد البحث عنه. |

**Returns:**  
com.aspose.slides.ICommentAuthor[] - المؤلف أو null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل المؤلف في الفهرس المحدد من المجموعة.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

يزيل أول ظهور للمؤلف المحدد في المجموعة.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | المؤلف المراد إزالته من المجموعة. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع المؤلفين من المجموعة.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

يعيد كائن تعداد يمكنه iterates خلال المجموعة.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```java
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

يعيد java iterator للمجموعة بأكملها.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس الابتدائي في مصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). للقراءة فقط boolean.

**Returns:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. للقراءة فقط Object.

**Returns:**  
java.lang.Object