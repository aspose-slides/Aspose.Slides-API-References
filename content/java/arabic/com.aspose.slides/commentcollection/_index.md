---
title: CommentCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من التعليقات لمؤلف واحد.
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

يمثل مجموعة من التعليقات الخاصة بمؤلف واحد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | أضف تعليقًا جديدًا في نهاية مجموعة. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | أضف تعليقًا حديثًا جديدًا في نهاية مجموعة. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | أدرج تعليقًا جديدًا إلى مجموعة في الفهرس المحدد. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | أدرج تعليقًا حديثًا جديدًا إلى مجموعة في الفهرس المحدد. |
| [toArray()](#toArray--) | إنشاء وإرجاع مصفوفة تحتوي على جميع التعليقات. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | إنشاء وإرجاع مصفوفة تحتوي على جميع التعليقات من النطاق المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد في مجموعة. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | يزيل أول ظهور للتعليق المحدد في مجموعة. |
| [clear()](#clear--) | يزيل جميع التعليقات من مجموعة. |
| [iterator()](#iterator--) | يُرجع عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُرجع مكرّر جافا للمجموعة بأكملها. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | يجد تعليقًا في المجموعة حسب الفهرس. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينقل جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يُرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا عبر الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يُرجع جذر المزامنة. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط  int .

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [Comment](../../com.aspose.slides/comment).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

أضف تعليقًا جديدًا في نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الصريح لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | شريحة في عرض تقديمي تُضيف إليها التعليق الجديد. |
| position | java.awt.geom.Point2D.Float | الموضع على شريحة حيث يتم إضافة التعليق الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment) - تعليق مضاف.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

أضف تعليقًا حديثًا جديدًا في نهاية مجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الصريح لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | شريحة في عرض تقديمي تُضيف إليها التعليق الحديث الجديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | شكل على شريحة يرتبط به التعليق الحديث الجديد. |
| position | java.awt.geom.Point2D.Float | الموضع على شريحة حيث يتم إضافة التعليق الحديث الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**الإرجاع:**
[IModernComment](../../com.aspose.slides/imoderncomment) - تعليق حديث مضاف.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

أدرج تعليقًا جديدًا إلى مجموعة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة حيث يجب إدراج التعليق. |
| text | java.lang.String | النص الصريح لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | شريحة في عرض تقديمي تُضيف إليها التعليق الجديد. |
| position | java.awt.geom.Point2D.Float | الموضع على شريحة حيث يتم إضافة التعليق الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment) - التعليق المُدرج.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

أدرج تعليقًا حديثًا جديدًا إلى مجموعة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة حيث يجب إدراج التعليق الحديث. |
| text | java.lang.String | النص الصريح لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | شريحة في عرض تقديمي تُضيف إليها التعليق الحديث الجديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | شكل على شريحة يرتبط به التعليق الحديث الجديد. |
| position | java.awt.geom.Point2D.Float | الموضع على شريحة حيث يتم إضافة التعليق الحديث الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**الإرجاع:**
[IModernComment](../../com.aspose.slides/imoderncomment) - التعليق الحديث المُدرج.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

ينشئ ويُرجع مصفوفة تحتوي على جميع التعليقات.

**الإرجاع:**
com.aspose.slides.IComment[] - مصفوفة من [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

ينشئ ويُرجع مصفوفة تحتوي على جميع التعليقات من النطاق المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس التعليق الأول الذي سيتم إرجاعه. |
| count | int | عدد التعليقات التي سيتم إرجاعها. |

**الإرجاع:**
com.aspose.slides.IComment[] - مصفوفة من [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد في مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

يزيل أول ظهور للتعليق المحدد في مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | التعليق الذي سيتم إزالته من مجموعة. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع التعليقات من مجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

يُرجع عدّادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

يُرجع مكرّر جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator للمجموعة بأكملها.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

يجد تعليقًا في المجموعة حسب الفهرس.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| idx | int | فهرس فريد للتعليق للعثور عليه  int . |

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment) - التعليق الموجود أو null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يُرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا عبر الخيوط). للقراءة فقط  boolean .

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يُرجع جذر المزامنة. للقراءة فقط  Object .

**الإرجاع:**
java.lang.Object