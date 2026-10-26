---
title: CommentCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من التعليقات لكاتب واحد.
type: docs
url: /ar/com.aspose.slides/commentcollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

يمثل مجموعة من التعليقات لكاتب واحد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الفعلية المحتواة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | إضافة تعليق جديد في نهاية المجموعة. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | إضافة تعليق حديث جديد في نهاية المجموعة. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | إدراج تعليق جديد إلى مجموعة في الفهرس المحدد. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | إدراج تعليق حديث جديد إلى مجموعة في الفهرس المحدد. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات من النطاق المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد في مجموعة. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | يزيل أول تكرار للتعليق المحدد في مجموعة. |
| [clear()](#clear--) | يزيل جميع التعليقات من مجموعة. |
| [iterator()](#iterator--) | يعيد عدّادًا يتنقل خلال المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر Java للمجموعة بأكملها. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | يبحث عن تعليق في المجموعة حسب الفهرس. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلية المحتواة في المجموعة. للقراءة فقط  int .

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [Comment](../../com.aspose.slides/comment).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

إضافة تعليق جديد في نهاية مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص العادي لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث يتم إضافة تعليق جديد. |
| position | android.graphics.PointF | الموضع على الشريحة حيث يتم إضافة تعليق جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment) - تم إضافة التعليق.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

إضافة تعليق حديث جديد في نهاية مجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص العادي لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث يتم إضافة تعليق حديث جديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل على الشريحة المرتبط به تعليق حديث جديد. |
| position | android.graphics.PointF | الموضع على الشريحة حيث يتم إضافة تعليق حديث جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**القيمة المرجعة:**
[IModernComment](../../com.aspose.slides/imoderncomment) - تم إضافة التعليق الحديث.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

إدراج تعليق جديد إلى مجموعة في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة حيث يجب إدراج التعليق. |
| text | java.lang.String | النص العادي لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث يتم إضافة تعليق جديد. |
| position | android.graphics.PointF | الموضع على الشريحة حيث يتم إضافة تعليق جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment) - تم إدراج التعليق.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

إدراج تعليق حديث جديد إلى مجموعة في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة حيث يجب إدراج التعليق الحديث. |
| text | java.lang.String | النص العادي لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث يتم إضافة تعليق حديث جديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل على الشريحة المرتبط به تعليق حديث جديد. |
| position | android.graphics.PointF | الموضع على الشريحة حيث يتم إضافة تعليق حديث جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**القيمة المرجعة:**
[IModernComment](../../com.aspose.slides/imoderncomment) - تم إدراج التعليق الحديث.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات.

**القيمة المرجعة:**
com.aspose.slides.IComment[] - مصفوفة من [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

ينشئ ويعيد مصفوفة تحتوي على جميع التعليقات من النطاق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول تعليق للإرجاع. |
| count | int | عدد التعليقات للإرجاع. |

**القيمة المرجعة:**
com.aspose.slides.IComment[] - مصفوفة من [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد في مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

يزيل أول تكرار للتعليق المحدد في مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | التعليق لإزالته من مجموعة. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع التعليقات من مجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

يعيد عدّادًا يتنقل خلال المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - مؤشر IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

يعيد مكرّر Java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - مؤشر java.util.Iterator للمجموعة بأكملها.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

يبحث عن تعليق في المجموعة حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| idx | int | فهرس فريد لتعليق للعثور عليه  int . |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment) - تم العثور على التعليق أو null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). للقراءة فقط  boolean .

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. للقراءة فقط  Object .

**القيمة المرجعة:**
java.lang.Object