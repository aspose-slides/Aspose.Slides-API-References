---
title: ICommentCollection
second_title: Aspose.Slides لجاڤا مرجع API
description: يمثل مجموعة من التعليقات لمؤلف واحد.
type: docs
url: /ar/com.aspose.slides/icommentcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

يمثل مجموعة من التعليقات لمؤلف واحد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يجلب العنصر في الفهرس المحدد. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | يضيف تعليقًا جديدًا في نهاية مجموعة. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | يضيف تعليقًا حديثًا جديدًا في نهاية مجموعة. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | يدخل تعليقًا جديدًا في مجموعة عند الفهرس المحدد. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | يدخل تعليقًا حديثًا جديدًا في مجموعة عند الفهرس المحدد. |
| [toArray()](#toArray--) | ينشئ ويُرجع مصفوفة تحتوي على جميع التعليقات. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويُرجع مصفوفة تحتوي على جميع التعليقات من النطاق المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد داخل مجموعة. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | يزيل الظهور الأول للتعليق المحدد في مجموعة. |
| [clear()](#clear--) | يزيل جميع التعليقات من مجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


يجلب العنصر في الفهرس المحدد. للقراءة فقط [IComment](../../com.aspose.slides/icomment).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


يضيف تعليقًا جديدًا في نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص العادي لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي التي يُضاف إليها التعليق الجديد. |
| position | java.awt.geom.Point2D.Float | الموقع على الشريحة الذي يُضاف إليه التعليق الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment) - التعليق المضاف.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


يضيف تعليقًا حديثًا جديدًا في نهاية مجموعة.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص العادي لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي التي يُضاف إليها التعليق الحديث الجديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل على الشريحة المرتبط بالتعليق الحديث الجديد. |
| position | java.awt.geom.Point2D.Float | الموقع على الشريحة الذي يُضاف إليه التعليق الحديث الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**القيمة المرجعة:**
[IModernComment](../../com.aspose.slides/imoderncomment) - التعليق الحديث المضاف.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


يدخل تعليقًا جديدًا في مجموعة عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة حيث يجب إدراج التعليق. |
| text | java.lang.String | النص العادي لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي التي يُضاف إليها التعليق الجديد. |
| position | java.awt.geom.Point2D.Float | الموقع على الشريحة الذي يُضاف إليه التعليق الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**القيمة المرجعة:**
[IComment](../../com.aspose.slides/icomment) - التعليق المُدرج.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


يدخل تعليقًا حديثًا جديدًا في مجموعة عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة حيث يجب إدراج التعليق الحديث. |
| text | java.lang.String | النص العادي لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي التي يُضاف إليها التعليق الحديث الجديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل على الشريحة المرتبط بالتعليق الحديث الجديد. |
| position | java.awt.geom.Point2D.Float | الموقع على الشريحة الذي يُضاف إليه التعليق الحديث الجديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**القيمة المرجعة:**
[IModernComment](../../com.aspose.slides/imoderncomment) - التعليق الحديث المُدرج.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


ينشئ ويُرجع مصفوفة تحتوي على جميع التعليقات.

**القيمة المرجعة:**
com.aspose.slides.IComment[] - مصفوفة من [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


ينشئ ويُرجع مصفوفة تحتوي على جميع التعليقات من النطاق المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول تعليق للإرجاع. |
| count | int | عدد التعليقات للإرجاع. |

**القيمة المرجعة:**
com.aspose.slides.IComment[] - مصفوفة من [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد داخل مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


يزيل الظهور الأول للتعليق المحدد في مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | التعليق الذي سيُزال من مجموعة. |

### clear() {#clear--}
```
public abstract void clear()
```


يزيل جميع التعليقات من مجموعة.