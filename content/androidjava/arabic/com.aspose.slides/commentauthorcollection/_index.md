---
title: CommentAuthorCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من مؤلفي التعليقات.
type: docs
url: /ar/com.aspose.slides/commentauthorcollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

يمثل مجموعة من مؤلفي التعليقات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يُعيد عدد العناصر التي تحتويها المجموعة فعليًا. |
| [get_Item(int index)](#get-Item-int-) | يُعيد العنصر في الفهرس المحدد. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | يضيف مؤلفًا جديدًا في نهاية المجموعة. |
| [toArray()](#toArray--) | ينشئ ويُعيد مصفوفة تحتوي على جميع المؤلفين. |
| [findByName(String name)](#findByName-java.lang.String-) | يبحث عن مؤلف في المجموعة حسب الاسم. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | يبحث عن مؤلف في المجموعة حسب الاسم والحروف الأولى. |
| [removeAt(int index)](#removeAt-int-) | يزيل المؤلف في الفهرس المحدد من المجموعة. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | يزيل أول ظهور للمؤلف المحدد في المجموعة. |
| [clear()](#clear--) | يزيل جميع المؤلفين من المجموعة. |
| [iterator()](#iterator--) | يُعيد عدًّا يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُعيد مِؤشر java للمجموعة بالكامل. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يُعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يُعيد جذر التزامن. |
### size() {#size--}
```
public final int size()
```

يُعيد عدد العناصر التي تحتويها المجموعة فعليًا. قابل للقراءة فقط int.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

يُعيد العنصر في الفهرس المحدد. قابل للقراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

يضيف مؤلفًا جديدًا في نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف الجديد. |
| initials | java.lang.String | الأحرف الأولى للمؤلف الجديد. |

**الإرجاع:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - كائن [ICommentAuthor](../../com.aspose.slides/icommentauthor) جديد.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

ينشئ ويُعيد مصفوفة تحتوي على جميع المؤلفين.

**الإرجاع:**
com.aspose.slides.ICommentAuthor[] - مصفوفة من [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

يبحث عن مؤلف في مجموعة حسب الاسم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف المراد العثور عليه. |

**الإرجاع:**
com.aspose.slides.ICommentAuthor[] - مؤلف أو null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

يبحث عن مؤلف في مجموعة حسب الاسم والحروف الأولى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف المراد العثور عليه. |
| initials | java.lang.String | الأحرف الأولى للمؤلف المراد العثور عليه. |

**الإرجاع:**
com.aspose.slides.ICommentAuthor[] - مؤلف أو null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل المؤلف في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر الذي سيتم إزالته. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

يزيل أول ظهور للمؤلف المحدد في مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | المؤلف الذي سيتم إزالته من المجموعة. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع المؤلفين من مجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

يُعيد عدًّا يمر عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

يُعيد مِؤشر java للمجموعة بالكامل.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - java.util.Iterator كامل للمجموعة.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يُعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). قابل للقراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يُعيد جذر التزامن. قابل للقراءة فقط Object.

**الإرجاع:**
java.lang.Object