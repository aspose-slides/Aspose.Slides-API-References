---
title: ICommentCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من التعليقات الخاصة بمؤلف واحد.
type: docs
url: /ar/com.aspose.slides/icommentcollection/
---
**جميع الواجهات التي تم تنفيذها:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

يمثل مجموعة من التعليقات الخاصة بمؤلف واحد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | إضافة تعليق جديد في نهاية المجموعة. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | إضافة تعليق حديث جديد في نهاية المجموعة. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | إدراج تعليق جديد في مجموعة في الفهرس المحدد. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | إدراج تعليق حديث جديد في مجموعة في الفهرس المحدد. |
| [toArray()](#toArray--) | إنشاء وإرجاع مصفوفة تحتوي على جميع التعليقات. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | إنشاء وإرجاع مصفوفة تحتوي على جميع التعليقات من النطاق المحدد. |
| [removeAt(int index)](#removeAt-int-) | إزالة العنصر في الفهرس المحدد داخل مجموعة. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | إزالة أول حدوث للتعليق المحدد في مجموعة. |
| [clear()](#clear--) | إزالة جميع التعليقات من مجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [IComment](../../com.aspose.slides/icomment).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

إضافة تعليق جديد في نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص العادي لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث سيتم إضافة تعليق جديد. |
| position | android.graphics.PointF | الموقع على الشريحة حيث سيتم إضافة تعليق جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**القيمة المرتجعة:**
[IComment](../../com.aspose.slides/icomment) - التعليق المضاف.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

إضافة تعليق حديث جديد في نهاية المجموعة.

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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص العادي لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث سيتم إضافة تعليق حديث جديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل على الشريحة المرتبط بتعليق حديث جديد. |
| position | android.graphics.PointF | الموقع على الشريحة حيث سيتم إضافة تعليق حديث جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**القيمة المرتجعة:**
[IModernComment](../../com.aspose.slides/imoderncomment) - التعليق الحديث المضاف.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

إدراج تعليق جديد في مجموعة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة يتم عنده إدراج التعليق. |
| text | java.lang.String | النص العادي لتعليق جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث سيتم إضافة تعليق جديد. |
| position | android.graphics.PointF | الموقع على الشريحة حيث سيتم إضافة تعليق جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق. |

**القيمة المرتجعة:**
[IComment](../../com.aspose.slides/icomment) - التعليق المدخل.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

إدراج تعليق حديث جديد في مجموعة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في مجموعة يتم عنده إدراج التعليق الحديث. |
| text | java.lang.String | النص العادي لتعليق حديث جديد. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة في العرض التقديمي حيث سيتم إضافة تعليق حديث جديد. |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل على الشريحة المرتبط بتعليق حديث جديد. |
| position | android.graphics.PointF | الموقع على الشريحة حيث سيتم إضافة تعليق حديث جديد. |
| creationTime | java.util.Date | وقت إنشاء التعليق الحديث. |

**القيمة المرتجعة:**
[IModernComment](../../com.aspose.slides/imoderncomment) - التعليق الحديث المدخل.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

إنشاء وإرجاع مصفوفة تحتوي على جميع التعليقات.

**القيمة المرتجعة:**
com.aspose.slides.IComment[] - مصفوفة من [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

إنشاء وإرجاع مصفوفة تحتوي على جميع التعليقات من النطاق المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول تعليق للارجاع. |
| count | int | عدد التعليقات للارجاع. |

**القيمة المرتجعة:**
com.aspose.slides.IComment[] - مصفوفة من [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

إزالة العنصر في الفهرس المحدد داخل مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس المستند إلى الصفر للعنصر الذي سيتم إزالته. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

إزالة أول حدوث للتعليق المحدد في مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | التعليق الذي سيتم إزالته من مجموعة. |

### clear() {#clear--}
```
public abstract void clear()
```

إزالة جميع التعليقات من مجموعة.